FROM mysql:8.0.33 
LABEL "Project"="vprofile"
LABEL "Author"="Vishwajeet"

ENV MYSQL_ROOT_PASSWORD="your_password"
ENV MYSQL_DATABASE="your_db"

ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql