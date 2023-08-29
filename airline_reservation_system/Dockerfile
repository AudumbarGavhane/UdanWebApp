# Use an official OpenJDK runtime as the base image
FROM openjdk:11-jre-slim

# Set the working directory in the container
WORKDIR /app

# Copy the Spring Boot executable JAR file to the container
COPY target/airline_reservation_system.jar .

# Expose the port that your Spring Boot app will run on
EXPOSE 8080

# Start the Spring Boot application
CMD ["java", "-jar", "airline_reservation_system.jar"]
