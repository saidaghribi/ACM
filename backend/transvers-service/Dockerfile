FROM alpine/java:21-jdk
RUN mkdir -p /app/jars/
COPY target/transvers-service.jar /app/jars/
EXPOSE 8093
ENTRYPOINT ["java", "-jar", "/app/jars/transvers-service.jar"]