FROM openjdk:latest
ADD target/GreenCommute-0.0.1-SNAPSHOT.jar /tmp
WORKDIR /tmp
EXPOSE 8000
ENTRYPOINT ["java", "-jar", "GreenCommute-0.0.1-SNAPSHOT.jar"]
