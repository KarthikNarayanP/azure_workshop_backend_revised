FROM openjdk:8-jdk-alpine
COPY build/libs/image-service-1.0.jar image-service-1.0.jar
EXPOSE 1433
EXPOSE 8183
ENTRYPOINT ["sh", "-c", "java -jar -Dspring.profiles.active=prod /image-service-1.0.jar"]