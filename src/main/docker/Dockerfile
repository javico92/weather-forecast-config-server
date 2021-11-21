FROM openjdk:10-jdk-slim

VOLUME /tmp
ADD config-server-*.jar app.jar
ADD logback.xml /conf/logback-dev.xml
ENTRYPOINT exec java $JAVA_OPTIONS -jar /app.jar
