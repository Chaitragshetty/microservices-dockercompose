FROM openjdk:11-jdk-stretch
WORKDIR /src/muzix
ADD /target/testdemo-0.0.1-SNAPSHOT.jar /src/muzix/testdemo-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java", "-jar", "testdemo-0.0.1-SNAPSHOT.jar"]
