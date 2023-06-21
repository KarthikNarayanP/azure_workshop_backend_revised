FROM openjdk:8-jdk-alpine
COPY build/libs/service-registry-1.0.jar service-registry-1.0.jar
EXPOSE 8180
ENTRYPOINT ["sh", "-c", "java -jar -Dspring.profiles.active=prod /service-registry-1.0.jar"]