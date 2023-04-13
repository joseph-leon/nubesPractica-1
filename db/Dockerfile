FROM mysql:latest

ENV MYSQL_ROOT_PASSWORD=pass123456789

ENV MYSQL_DATABASE=mydb

COPY ./mydb.sql /docker-entrypoint-initdb.d/

EXPOSE 3306
