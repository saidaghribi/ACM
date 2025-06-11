FROM alpine/java:21-jdk
RUN mkdir -p /app/jars/
COPY target/credit-service.jar /app/jars/
EXPOSE 8081
ENTRYPOINT ["java", "-jar", "/app/jars/credit-service.jar"]