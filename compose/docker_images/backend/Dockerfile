FROM chainguard/jdk:latest

COPY /backend /backend
CMD /backend/gradlew build

ENTRYPOINT ["java","-jar","/backend/build/libs/cz.backend.app-all.jar"]