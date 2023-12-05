FROM eclipse-temurin:17-jre-alpine

COPY ./target/jci-application-secure.jar jci-application-secure.jar

ENTRYPOINT ["java","-Xmx2g", "-jar","/jci-application-secure.jar"]
