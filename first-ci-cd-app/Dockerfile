# Use official JDK base image
FROM openjdk:17-jdk-slim

# Add the jar file into the image
COPY target/*.jar app.jar

# Command to run the JAR
ENTRYPOINT ["java", "-jar", "/app.jar"]