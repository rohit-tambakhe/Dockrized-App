FROM openjdk:14-jdk-alpine
ADD ./target/notificationService-jar-with-dependencies.jar /opt/Codestub/upgrad-sweet-home-docker-deployment/notificationService-jar-with-dependencies.jar
WORKDIR /opt/Codestub/upgrad-sweet-home-docker-deployment
ENV PATH="${PATH}:${JAVA_HOME}/bin"
EXPOSE 8082
ENTRYPOINT [ "java", "-jar", "/opt/Codestub/upgrad-sweet-home-docker-deployment/notificationService-jar-with-dependencies.jar"]
