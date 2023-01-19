FROM eclipse-temurin:11-jre-alpine

COPY ./target/jci-application-1.2.jar jci-application-1.2.jar

ENTRYPOINT ["java","-Xmx1g", "-jar","/jci-application-1.2.jar"]
