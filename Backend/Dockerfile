FROM eclipse-temurin:17-jre
WORKDIR /app
COPY Backend/target/backend-0.0.1-SNAPSHOT.jar app.jar
EXPOSE 8080
CMD ["java", "-Dserver.port=8080", "-Dspring.profiles.active=prod", "-jar", "app.jar"]
