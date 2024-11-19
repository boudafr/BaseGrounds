FROM openjdk:21
COPY copyBE /app
CMD /app/gradlew build
ENTRYPOINT ["java","-jar","/app/build/libs/cz.backend.app-0.0.1.jar"]
