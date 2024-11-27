FROM openjdk:alpine

WORKDIR /testdir/java

COPY calc.java .

RUN javac calc.java

CMD [ "java", "calc" ]
