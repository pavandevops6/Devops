FROM tomcat:8-jre11

RUN rm -rf /opt/tomcat/webapps/*

COPY target/vprofile-v2.war /opt/tomcat/webapps/ROOT.war

EXPOSE 8080
CMD ["catalina.sh", "run"]

