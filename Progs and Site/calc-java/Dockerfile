FROM openjdk:22-slim
WORKDIR /test/java
COPY calc.java /test/java
RUN javac calc.java
CMD [ "java", "calc" ]