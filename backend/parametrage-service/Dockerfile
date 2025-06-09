FROM alpine/java:21-jdk
RUN mkdir -p /app/jars/
COPY target/parametrage-service.jar /app/jars/
EXPOSE 8091
ENTRYPOINT ["java", "-jar", "/app/jars/parametrage-service.jar"]