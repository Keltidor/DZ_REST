FROM openjdk:8-jdk-alpine
EXPOSE 8080
ADD target/DZ_REST-1.0-SNAPSHOT.jar /authorize.jar
ENTRYPOINT ["java", "-jar", "/authorize.jar"]