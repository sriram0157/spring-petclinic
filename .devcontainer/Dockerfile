# Use Ubuntu base with OpenJDK
FROM ubuntu:22.04
run apt update \
    && apt -get install openjdk-17-jdk -y

# Set working directory
WORKDIR /app

# Copy built JAR file into container
 #COPY target/*.jar app.jar

# Run the application
#ENTRYPOINT ["java","-jar","app.jar"]
