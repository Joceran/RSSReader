FROM java:8


# forked repository
#RUN git clone https://github.com/Netflix/recipes-rss.git recipes-rss

#build the netflix rss reader

WORKDIR /
ENV APP_ENV=dev
#RUN ./gradlew clean build

ADD rss-edge-0.1.0-SNAPSHOT.jar .

EXPOSE 9090 9092

#start jar

CMD ["java","-jar","rss-edge-0.1.0-SNAPSHOT.jar"]
