FROM tomcat:7.0.85-jre8

ADD eureka.war /usr/local/tomcat/webapps/

ADD server.xml /usr/local/tomcat/conf/

ADD tomcat-users.xml /usr/local/tomcat/conf/

EXPOSE 80

CMD ["catalina.sh", "run"]
