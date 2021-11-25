FROM openjdk:10-jdk-slim

VOLUME /tmp
ADD weather-forecast-config-server-*.jar app.jar
ADD logback.xml /conf/logback.xml
ENTRYPOINT exec java $JAVA_OPTIONS -jar /app.jar
