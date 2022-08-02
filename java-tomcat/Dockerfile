FROM tomcat:8.0
# RUN cp -a **/*.war /usr/local/tomcat/webapps/
COPY . /usr/local/tomcat/webapps/
EXPOSE 8080
CMD ["catalina.sh", "run"]