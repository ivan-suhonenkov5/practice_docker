FROM openjdk:alpine

LABEL version="1.0.23"

WORKDIR /app/practice3

COPY . /app/practice3/

RUN javac calc.java

CMD ["java", "calc"]