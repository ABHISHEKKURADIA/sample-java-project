FROM maven
WORKDIR /app

COPY pom.xml .

COPY src ./src

COPY test ./test

EXPOSE 8080

ENTRYPOINT ["java","-jar","app.jar"]
