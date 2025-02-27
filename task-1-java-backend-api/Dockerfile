FROM openjdk:17-jdk-slim
COPY target/kaiburr-0.0.1-SNAPSHOT.jar task-api.jar

EXPOSE 8080

ENTRYPOINT ["java", "-jar", "task-api.jar"]

