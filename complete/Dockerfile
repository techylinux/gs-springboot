FROM amazoncorretto:latest
WORKDIR /opt/app
# Accept a build argument for the JAR name
ARG JAR_FILE
COPY target/${JAR_FILE} app.jar
ENTRYPOINT ["java","-jar","app.jar"]
