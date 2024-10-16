FROM openjdk:11-jdk-slim
ENV API_KEY="fakeapikey"
ENV DB_PASSWORD="fakedbpassword"
COPY ./target/java-secret-demo.jar /usr/app/
WORKDIR /usr/app
ENTRYPOINT ["java", "-jar", "java-secret-demo.jar"]
