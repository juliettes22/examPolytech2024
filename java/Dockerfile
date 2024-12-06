FROM eclipse-temurin:8-jre-alpine

LABEL maintainer="juliette" 

WORKDIR /usr/src/app

COPY  target/app.jar app.jar

EXPOSE 8448

CMD ["java", "-jar", "app.jar"]


