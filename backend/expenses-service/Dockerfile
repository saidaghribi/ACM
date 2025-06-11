FROM openjdk:21-jdk-slim
RUN mkdir -p /app/jars/
COPY target/expenses-service.jar /app/jars/
EXPOSE 8096
ENTRYPOINT ["java", "-jar", "/app/jars/expenses-service.jar"]