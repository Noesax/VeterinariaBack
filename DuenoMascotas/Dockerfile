FROM openjdk:21-jdk-slim
ARG JAR_FILE=target/DuenoMascotas-0.0.1-SNAPSHOT.jar
COPY ${JAR_FILE} DuenoMascotas.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "DuenoMascotas.jar"]