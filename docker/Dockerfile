FROM openjdk:11-jre-slim
WORKDIR /usr/src/app
COPY /C/Users/tejas/.jenkins/workspace/Website/target/*.jar /usr/src/app/
CMD ["java", "-jar", "webapp.app-1.0-SNAPSHOT.jar"]
EXPOSE 3000


