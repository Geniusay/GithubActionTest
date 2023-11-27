FROM adoptopenjdk:11-jre-hotspot
COPY *.jar /test-hello.jar
COPY /src/main/resources/you-cant-see-that.yml /you-cant-see-that.yml
ARG Active

ENV Active=${Active}

EXPOSE 8081


ENTRYPOINT ["java","-jar","/test-hello.jar"]
