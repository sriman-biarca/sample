FROM openjdk:8-jdk-alpine
VOLUME /tmp
ARG JAR_FILE
COPY ${JAR_FILE} hellow-world.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/hellow-world.jar"]