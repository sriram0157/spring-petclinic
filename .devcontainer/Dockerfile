# Use Ubuntu base with OpenJDK
FROM ubuntu:22.04

# Install Java
RUN apt-get update && apt-get install -y openjdk-17-jdk && rm -rf /var/lib/apt/lists/*

# Set working directory
WORKDIR /app

# Copy built JAR file into container
COPY target/*.jar app.jar

# Run the application
ENTRYPOINT ["java","-jar","app.jar"]
