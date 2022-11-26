FROM openjdk:8-jdk-alpine
RUN "ls -la"
COPY **/target/backend-spring.jar .
EXPOSE 8080
ENTRYPOINT ["java","-jar","/backend-spring.jar"]
