FROM eclipse-temurin:17-jre-alpine
WORKDIR /app
COPY build/libs/social_network-0.0.1-SNAPSHOT.jar app.jar
ENTRYPOINT ["java", "-jar", "app.jar"]
EXPOSE 8080