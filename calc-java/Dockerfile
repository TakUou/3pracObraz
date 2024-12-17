FROM openjdk:alpine

WORKDIR /calckdir/java

COPY . /calckdir/java

RUN javac calc.java

CMD [ "java", "calc" ]