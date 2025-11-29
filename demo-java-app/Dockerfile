# Base image
FROM eclipse-temurin:21-jdk-alpine

# Set working directory
WORKDIR /opt/app

# Copy the built jar
COPY target/demo-java-app.jar app.jar

# Run the app
ENTRYPOINT ["java", "-jar", "app.jar"]
