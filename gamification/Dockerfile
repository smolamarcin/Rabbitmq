FROM openjdk:8
VOLUME /tmp
COPY target/gamification-1.0.0.jar app.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","app.jar"]