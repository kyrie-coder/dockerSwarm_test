FROM registry.openanolis.cn/openanolis/mysql:8.0.30-8.6
COPY ./init.sql /docker-entrypoint-initdb.d/

RUN chmod a+x /docker-entrypoint-initdb.d/init.sql
