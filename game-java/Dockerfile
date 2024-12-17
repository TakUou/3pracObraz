FROM openjdk:alpine

WORKDIR /gamedir/java

COPY . /gamedir/java

RUN javac game.java

CMD [ "java", "game" ]