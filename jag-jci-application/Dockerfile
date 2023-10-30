FROM eclipse-temurin:17-jre-alpine

COPY ./target/jci-application.jar jci-application.jar

ENTRYPOINT ["java","-Xmx2g", "-jar","/jci-application.jar"]
