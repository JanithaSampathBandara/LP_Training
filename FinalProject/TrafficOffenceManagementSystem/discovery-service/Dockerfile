FROM openjdk:8
ADD target/docker-discovery-service.jar docker-discovery-service.jar
EXPOSE 8761
ENTRYPOINT ["java", "-jar", "docker-discovery-service.jar"]