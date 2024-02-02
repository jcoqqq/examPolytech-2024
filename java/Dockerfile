FROM maven:3.6.3-jdk-8

LABEL maintainer="Julien"

WORKDIR /app

COPY . .

RUN mvn clean package -DskipTests


EXPOSE 8448

CMD ["java", "-jar", "target/java-0.0.1-SNAPSHOT.jar"]
