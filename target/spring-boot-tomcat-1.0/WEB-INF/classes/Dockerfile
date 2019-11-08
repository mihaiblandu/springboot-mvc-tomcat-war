FROM tomcat:8.0.20-jre8
COPY target/app.war /usr/local/tomcat/webapps/app.war
COPY tomcat-users.xml /usr/local/tomcat/conf/
COPY context.xml /usr/local/tomcat/webapps/manager/META-INF/
CMD ["catalina.sh","run"]
