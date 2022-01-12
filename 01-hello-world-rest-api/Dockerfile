FROM openjdk:8-jdk-alpine
VOLUME /tmp
EXPOSE 8080
ADD target/cloudbuild-java-hello-world.jar app.jar
ENTRYPOINT [ "sh", "-c", "java -jar /app.jar" ]