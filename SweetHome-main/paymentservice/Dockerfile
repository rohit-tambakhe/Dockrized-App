FROM openjdk:14-jdk-alpine
ADD ./target/paymentService.jar /opt/Codestub/upgrad-sweet-home-docker-deployment/paymentService.jar
WORKDIR /opt/Codestub/upgrad-sweet-home-docker-deployment
ENV PATH="${PATH}:${JAVA_HOME}/bin"
EXPOSE 8083
ENTRYPOINT [ "java", "-jar", "/opt/Codestub/upgrad-sweet-home-docker-deployment/paymentService.jar"]
