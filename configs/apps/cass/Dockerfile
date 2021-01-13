FROM adoptopenjdk/openjdk11:jre-11.0.9.1_1-alpine

RUN apk --no-cache add curl

COPY /SimpleRest.jar /SimpleRest.jar
CMD ["java", "-jar", "/SimpleRest.jar"]