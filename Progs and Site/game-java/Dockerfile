FROM openjdk:22-slim
WORKDIR /test/java
COPY game.java /test/java
RUN javac game.java
CMD [ "java", "game" ]