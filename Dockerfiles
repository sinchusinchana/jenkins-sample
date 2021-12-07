FROM openjdk:11

EXPOSE 8080

ADD target/jenkins-sample.jar jenkins-sample.jar

ENTRYPOINT ["java","-jar","/jenkins-sample.jar"]