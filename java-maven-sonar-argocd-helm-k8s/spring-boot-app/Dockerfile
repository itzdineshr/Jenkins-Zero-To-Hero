FROM adoptopenjdk/openjdk11:alpine-jre

WORKDIR /app

COPY /target/spring-boot-web.jar app.jar

ENTRYPOINT [ "java","-jar","app.jar" ]