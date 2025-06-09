FROM alpine/java:21-jdk
RUN mkdir -p /app/jars/
COPY target/reporting-service.jar /app/jars/
EXPOSE 8099
ENTRYPOINT ["java", "-jar", "/app/jars/reporting-service.jar"]