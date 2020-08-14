FROM openjdk:8
ADD /target/docker-sample.jar docker-sample.jar
EXPOSE 8085
ENTRYPOINT ["java", "-jar", "docker-sample.jar"]