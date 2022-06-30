FROM mysql
ENV MYSQL_ALLOW_EMPTY_PASSWORD=yes
COPY ./testdump.sql /docker-entrypoint-initdb.d/
EXPOSE 3306
