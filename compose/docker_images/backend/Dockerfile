FROM alpine/java:22-jdk

COPY /cz.backend.app-all.jar /cz.backend.app-all.jar

EXPOSE 8080/tcp

ENTRYPOINT ["java","-jar","cz.backend.app-all.jar"]