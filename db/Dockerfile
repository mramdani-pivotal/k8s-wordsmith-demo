FROM postgres:10.0-alpine

COPY words.sql /docker-entrypoint-initdb.d/
RUN  chmod 777 /docker-entrypoint-initdb.d/words.sql