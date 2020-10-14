FROM adoptopenjdk:11-jre-hotspot
EXPOSE 8082
ADD target/spring-rest-maven.jar spring-rest-maven.jar
ENTRYPOINT ["java","-jar","spring-rest-maven.jar"]