FROM tomcat:8.0

ENV DB_HOSTNAME=localhost
ENV DB_USER=sveda_service
ENV DB_PASSWORD=webco123
ENV DB_PORT=3306
ENV DB_NAME=superveda_db
ENV DB_TYPE=mysql

# Deploy Superveda Web App & Tomcat config
RUN rm -Rf /usr/local/tomcat/webapps/*
COPY tomcat/superveda.war /usr/local/tomcat/webapps/superveda.war

EXPOSE 8080
