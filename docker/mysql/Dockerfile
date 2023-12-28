FROM mysql:8.0

ENV MYSQL_DATABASE=portfolio
ENV MYSQL_ROOT_PASSWORD=123456

COPY docker/mysql/init.sql /docker-entrypoint-initdb.d/
