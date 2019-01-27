FROM mysql:5.6

ENV MYSQL_DATABASE=superveda_db
ENV MYSQL_ROOT_PASSWORD=root12
ENV MYSQL_USER=sveda_service
ENV MYSQL_PASSWORD=webco123

COPY superveda_db.sql /docker-entrypoint-initdb.d/superveda_db.sql

EXPOSE 3306
