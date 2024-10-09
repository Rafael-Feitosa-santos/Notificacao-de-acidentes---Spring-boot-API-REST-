FROM eclipse-temurin:22
VOLUME /tmp
EXPOSE 8080
ARG JAR_FILE=target/Notificacao-de-acidentes-0.0.1-SNAPSHOT.jar
ADD ${JAR_FILE} app.jar
ENTRYPOINT ["java","-jar","/app.jar"]