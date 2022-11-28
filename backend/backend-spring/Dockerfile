FROM openjdk:8-jdk-alpine

RUN mvn -f **/pom.xml clean package --batch-mode -DskipTests
FROM openjdk:17-alpine

COPY **/target/backend-spring.jar backend-spring.jar
EXPOSE 8080
ENTRYPOINT ["java","-jar","/backend-spring.jar"]
