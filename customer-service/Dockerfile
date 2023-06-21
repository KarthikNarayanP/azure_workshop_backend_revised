FROM openjdk:8-jdk-alpine
COPY build/libs/customer-service-1.0.jar customer-service-1.0.jar
EXPOSE 1433
EXPOSE 8182
ENTRYPOINT ["sh", "-c", "java -jar -Dspring.profiles.active=prod /customer-service-1.0.jar"]