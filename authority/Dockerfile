FROM malefeng/jre8
COPY authority-0.0.1-SNAPSHOT.jar /app.jar
CMD java -jar -Dserver.port=8081 -Deureka_host=localhost app.jar
EXPOSE 8081
MAINTAINER mlf