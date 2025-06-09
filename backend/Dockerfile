FROM alpine/java:21-jdk
RUN mkdir -p /app/jars/
COPY target/gateway-service.jar /app/jars/
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "/app/jars/gateway-service.jar"]