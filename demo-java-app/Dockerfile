FROM openjdk:21-jdk-slim
ARG artifact=target/demo-java-app.jar
WORKDIR /opt/app
COPY ${artifact} app.jar
ENTRYPOINT ["java","-jar","app.jar"]
