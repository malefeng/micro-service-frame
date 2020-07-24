FROM malefeng/jre8
COPY gateway-0.0.1-SNAPSHOT.jar /app.jar
CMD java -jar -Dserver.port=8080 -Deureka_host=localhost app.jar
EXPOSE 8080
MAINTAINER mlf