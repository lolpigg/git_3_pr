# Используем официальный образ OpenJDK
FROM openjdk:11-jdk-slim
WORKDIR /app
COPY game.java .
RUN javac game.java
CMD ["java", "game"]
