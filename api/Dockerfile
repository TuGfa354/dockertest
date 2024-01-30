# Use OpenJDK 17 as the base image
FROM eclipse-temurin:21-jdk-alpine

# Set the working directory inside the container
WORKDIR /app

# Copy the packaged Spring Boot application JAR file into the container
COPY target/BackVaguada-0.0.1-SNAPSHOT.jar app.jar

# Specify the command to run the Spring Boot application
CMD ["java", "-jar", "app.jar"]
