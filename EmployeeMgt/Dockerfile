FROM openjdk:19-jdk

# Set the working directory inside the container
WORKDIR /app

# Copy the JAR file into the container
COPY target/RegisterLogin-0.0.1-SNAPSHOT.jar .

# Expose the port on which your Spring Boot application runs
EXPOSE 8085

# Set environment variables for MySQL
ENV MYSQL_HOST=mysql \
    MYSQL_PORT=3306 \
    MYSQL_DATABASE=dboffice \
    MYSQL_USER=root \
    MYSQL_PASSWORD=Daddy1234.

# Run the Spring Boot application
CMD ["java", "-jar", "RegisterLogin-0.0.1-SNAPSHOT.jar"]
