FROM adoptopenjdk:11-jre-hotspot

ARG artifact=target/spring-boot-web.jar

# creating working directory
WORKDIR /opt/app

# copying the .jar file
COPY ${artifact} app.jar

ENTRYPOINT ["java","-jar","app.jar"]

# ref: https://hub.docker.com/_/adoptopenjdk
