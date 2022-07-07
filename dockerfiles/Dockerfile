FROM openjdk:8

WORKDIR /docker

COPY /*.jar docker/
EXPOSE 8080
# ENTRYPOINT ["java", "-jar", "demo-0.0.1-SNAPSHOT.jar"]
# ENTRYPOINT ["java", "-jar", "spring-boot-docker-0.0.1-SNAPSHOT.jar"]
ENTRYPOINT ["java", "-jar", "./docker/spring-music-1.0.jar"]


