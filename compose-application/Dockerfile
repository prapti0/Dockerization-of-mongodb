FROM openjdk:11-jre-slim

# Copy the .jar file to the app folder
COPY ./application.jar /usr/local/app/spring-boot-mongo.jar

# Expose the app port (8080)
EXPOSE 8080

# Run the Java application
CMD ["java", "-jar", "/usr/local/app/spring-boot-mongo.jar"]

