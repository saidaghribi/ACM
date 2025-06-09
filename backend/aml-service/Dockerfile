FROM eclipse-temurin:21-jdk-alpine
RUN mkdir -p /app/jars/
COPY target/aml-service.jar /app/jars/
EXPOSE 8098
ENTRYPOINT ["java", "-jar", "/app/jars/aml-service.jar"]