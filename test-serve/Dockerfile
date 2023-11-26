FROM adoptopenjdk:11-jre-hotspot
COPY *.jar /test-serve.jar

EXPOSE 8080

ENTRYPOINT ["java","-jar","/test-serve.jar"]
