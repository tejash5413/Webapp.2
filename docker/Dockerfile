FROM openjdk:8u151-jdk-alpine3.7
EXPOSE 8070
ENV APP_HOME /usr/src/app
COPY target/webapp.app-1.0-SNAPSHOT.jar $APP_HOME/
WORKDIR $APP_HOME
ENTRYPOINT exec java -jar webapp.app-1.0-SNAPSHOT.jar



