FROM ibm-semeru-runtimes:open-18-jre-focal
VOLUME /tmp
COPY target/demo-backend-ev-0.0.1-SNAPSHOT.jar app.jar
ENV JAVA_OPTS=""
ENTRYPOINT exec java -jar /app.jar --debug