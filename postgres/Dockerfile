FROM postgres:16.4

RUN mkdir -p /docker-entrypoint-initdb.d

COPY init-user-db.sh /docker-entrypoint-initdb.d
