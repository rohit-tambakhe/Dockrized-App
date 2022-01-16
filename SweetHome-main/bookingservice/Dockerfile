FROM openjdk:14-jdk-alpine
ADD ./target/bookingService.jar /opt/Codestub/upgrad-sweet-home-docker-deployment/bookingService.jar
WORKDIR /opt/Codestub/upgrad-sweet-home-docker-deployment
ENV PATH="${PATH}:${JAVA_HOME}/bin"
EXPOSE 8080
ENTRYPOINT [ "java", "-jar", "/opt/Codestub/upgrad-sweet-home-docker-deployment/bookingService.jar"]
