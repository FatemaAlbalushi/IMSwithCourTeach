
FROM openjdk:17-jdk-alpine
WORKDIR /app
RUN apk add --no-cache maven
COPY . /app
RUN mvn clean package
EXPOSE 8080
CMD ["javs","-jar","target/IMShibernate-0.0.1-SNAPSHOT.jar"]