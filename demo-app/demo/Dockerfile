FROM adoptopenjdk/openjdk17:alpine-jre

# saving artifact as a variable 
ARG artifact=target/demo-0.0.1-SNAPSHOT.jar

# creating working directory
WORKDIR /opt/app

# copying the .jar file
COPY ${artifact} app.jar

ENTRYPOINT ["java","-jar","app.jar"]
