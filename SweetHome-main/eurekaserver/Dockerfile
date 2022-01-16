FROM openjdk:14-jdk-alpine
ADD ./target/eurekaServer.jar /opt/Codestub/upgrad-sweet-home-docker-deployment/eurekaServer.jar
WORKDIR /opt/Codestub/upgrad-sweet-home-docker-deployment
ENV PATH="${PATH}:${JAVA_HOME}/bin"
EXPOSE 8761
ENTRYPOINT [ "java", "-jar", "/opt/Codestub/upgrad-sweet-home-docker-deployment/eurekaServer.jar"]
