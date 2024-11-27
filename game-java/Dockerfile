FROM openjdk:alpine

WORKDIR /testdir/javagame

COPY game.java /testdir/javagame/

RUN javac game.java

CMD [ "java", "game"]
