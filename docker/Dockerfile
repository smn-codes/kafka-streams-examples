FROM openjdk:8-jre-alpine

RUN mkdir /app

WORKDIR /app

COPY kafka.stream.examples-*.jar /app/kafka.stream.examples.jar

CMD ["java", "-jar", "/app/kafka.stream.examples.jar"]