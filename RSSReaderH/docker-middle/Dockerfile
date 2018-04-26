FROM java:8

RUN apt-get update && apt-get install -y git wget libgradle-core-java

RUN git clone https://github.com/Netflix/recipes-rss.git

WORKDIR ./recipes-rss/
ADD middletier.properties ./rss-middletier/src/main/resources/
RUN ./gradlew clean build -x javadoc

ENV APP_ENV=dev 
CMD java -jar rss-middletier/build/libs/rss-middletier-*SNAPSHOT.jar
