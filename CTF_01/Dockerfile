# Dockerfile

# Use an official Java runtime as a parent image
FROM openjdk:15.0.2-jdk-slim-buster

# Set the working directory to /app
WORKDIR /app

# Copy the jar file into the container
COPY CTF_01.jar /app

# Run the jar file
CMD ["java", "-jar", "CTF_01.jar"]