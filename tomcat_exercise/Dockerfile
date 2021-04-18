FROM tomcat:alpine

RUN wget https://tomcat.apache.org/tomcat-7.0-doc/appdev/sample/sample.war
RUN mv sample.war /usr/local/tomcat/webapps/
COPY index.html /usr/local/tomcat/webapps/sample/index.html
