#Start with a base image containing java runtime
From openjdk:26-ea-17-jdk-slim

#Information around who maintains the image
MAINTAINER prakhar10104701

#Add the application jar to the image
COPY target/accounts-0.0.1-SNAPSHOT.jar accounts-0.0.1-SNAPSHOT.jar

#execute the application
ENTRYPOINT ["java", "-jar", "accounts-0.0.1-SNAPSHOT.jar"]
