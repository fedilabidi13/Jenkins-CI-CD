# Use an official OpenJDK runtime as a parent image
FROM openjdk:19

# Set the working directory to /app
WORKDIR /app

# Copy the JAR file from the host to the container
COPY target/khaddem-4.1.jar /app/app.jar
EXPOSE 8089
# Specify the command to run your application
CMD ["java", "-jar", "app.jar"]