//FROM openjdk:8u151-jdk-alpine3.7
//EXPOSE 8070
//ENV APP_HOME /usr/src/app
//COPY target/webapp.app-1.0-SNAPSHOT.jar $APP_HOME/app.jar
//WORKDIR $APP_HOME
//ENTRYPOINT exec java -jar app.jar//
FROM openjdk:17-jdk-alpine
EXPOSE 8070
COPY target/webapp.app-1.0-SNAPSHOT.jar /usr/src/app/app.jar
WORKDIR /usr/src/app
CMD ["java", "-jar", "app.jar"]




