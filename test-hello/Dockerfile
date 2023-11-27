FROM adoptopenjdk:11-jre-hotspot
COPY *.jar /test-hello.jar
ARG Active

ENV Active=${Active}

EXPOSE 8081


ENTRYPOINT ["java","-jar","/test-hello.jar"]
