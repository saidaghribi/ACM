FROM alpine/java:21-jdk
RUN mkdir -p /app/jars/
COPY target/ged-service.jar /app/jars/
EXPOSE 8095
ENTRYPOINT ["java", "-jar", "/app/jars/ged-service.jar"]