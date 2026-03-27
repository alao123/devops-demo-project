FROM eclipse-temurin:21-jre-alpine
ARG artifact=target/demo-java-app.jar
WORKDIR /opt/app
COPY ${artifact} app.jar
ENTRYPOINT ["java","-jar","app.jar"]
