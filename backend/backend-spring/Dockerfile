FROM openjdk:8-jdk-alpine
WORKDIR /app/sonar
COPY target/backend-spring.jar ./
EXPOSE 8080
ENTRYPOINT ["java","-jar","/backend-spring.jar"]
