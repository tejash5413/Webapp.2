FROM openjdk:11-jre-slim
COPY C:/Users/tejas/.jenkins/workspace/Website/target/*.jar /usr/src/app/
ENV APP_HOME /usr/src/app
WORKDIR $APP_HOME
CMD ["java", "-jar", "webapp.app-1.0-SNAPSHOT.jar"]
EXPOSE 3000


