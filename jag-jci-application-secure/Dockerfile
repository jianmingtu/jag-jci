FROM eclipse-temurin:11-jre-alpine

COPY ./target/jci-application-secure.jar jci-application-secure.jar

ENTRYPOINT ["java","-Xmx1g", "-jar","/jci-application-secure.jar"]
