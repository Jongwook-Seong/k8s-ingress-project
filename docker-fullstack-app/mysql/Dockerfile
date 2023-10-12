FROM --platform=linux/x86_64 mysql:5.7

COPY ./sqls/initialize.sql /docker-entrypoint-initdb.d/
COPY ./my.cnf /etc/mysql/conf.d/my.cnf
