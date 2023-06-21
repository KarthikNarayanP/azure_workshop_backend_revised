FROM openjdk:8-jdk-alpine
COPY build/libs/payment-service-1.0.jar payment-service-1.0.jar
EXPOSE 1433
EXPOSE 8184
ENTRYPOINT ["sh", "-c", "java -jar -Dspring.profiles.active=prod /payment-service-1.0.jar"]