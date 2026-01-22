FROM tomcat:9.0-jdk11

RUN rm -rf /usr/local/tomcat/webapps/*

COPY target/project_3.war /usr/local/tomcat/webapps/project_3.war

EXPOSE 8080

CMD ["catalina.sh", "run"]
