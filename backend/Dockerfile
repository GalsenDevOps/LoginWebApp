# Use an official OpenJDK runtime as a parent image
FROM openjdk:11-jre-slim

# Maintainer information
LABEL maintainer="galsendevops@gmail.com"

# Set the working directory inside the container
WORKDIR /app

# Copy the JAR file from the local machine to the container
COPY target/backend-service.jar /app/backend-service.jar

# Expose the port the backend service will run on
EXPOSE 8082

# Command to run the backend service
CMD ["java", "-jar", "backend-service.jar"]
