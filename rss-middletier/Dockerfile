FROM java:8

#ENV INSPECTIT_CONFIG_HOME /agent-config

#RUN git clone https://github.com/Netflix/recipes-rss.git recipes-rss

#download the agent
WORKDIR /
#RUN wget https://github.com/inspectIT/inspectIT/releases/download/1.6.6.76/inspectit-agent-sun1.5.zip
#RUN unzip inspectit-agent-sun*.zip


#build the netflix rss reader
#WORKDIR /recipes-rss
ENV APP_ENV=dev
#RUN ./gradlew clean build




#start jar
WORKDIR /

ADD rss-middletier-0.1.0-SNAPSHOT.jar .

#EXPOSE 9090 9092

CMD ["java","-jar","rss-middletier-0.1.0-SNAPSHOT.jar"]
