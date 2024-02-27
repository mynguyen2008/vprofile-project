FROM mysql:8.0.33
LABEL "Project"="VProfile"
LABEL "Author"="MyNguyen"

ENV MYSQL_ROOT_PASSWORD="vprofilepass"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql docker-entrypoint-initdb.db.d/db_backup.sql
