FROM openjdk:11
VOLUME /tmp
EXPOSE 8080
COPY backend/target/*.jar dscatalog.jar
ENTRYPOINT ["java","-jar","/dscatalog.jar"]