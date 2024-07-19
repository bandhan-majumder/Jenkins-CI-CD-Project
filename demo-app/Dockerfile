FROM adoptopenjdk/openjdk17:alpine-jre

# saving artifact as a variable 
ARG artifact=target/spring-boot-web.jar

# creating working directory
WORKDIR /opt/app

# copying the .jar file
COPY ${artifact} app.jar

ENTRYPOINT ["java","-jar","app.jar"]
