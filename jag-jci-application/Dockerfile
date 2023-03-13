FROM eclipse-temurin:11-jre-alpine

COPY ./target/jci-application.jar jci-application.jar

ENTRYPOINT ["java","-Xmx1g", "-jar","/jci-application.jar"]
