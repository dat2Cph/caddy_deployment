# Start with the Amazon Corretto 17 base image
FROM amazoncorretto:17

# Copy the jar file into the image
COPY ./app.jar /app.jar

# Expose the port your app runs on
EXPOSE 7070

# Command to run your app
CMD ["java", "-jar", "/app.jar"]
