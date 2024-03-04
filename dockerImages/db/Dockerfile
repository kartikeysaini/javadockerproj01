FROM mysql:8.0.33
LABEL "AUTHOR"="Kartikey"

ENV MYSQL_ROOT_PASSWORD="abcd@123"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql

