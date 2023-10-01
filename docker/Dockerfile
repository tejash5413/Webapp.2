FROM openjdk:11-jre-slim
EXPOSE 8050
ENV APP_HOME /usr/src/app
COPY target/webapp.app-1.0-SNAPSHOT.jar $APP_HOME/app.jar
WORKDIR $APP_HOME
ENTRYPOINT exec java -jar app.jar



