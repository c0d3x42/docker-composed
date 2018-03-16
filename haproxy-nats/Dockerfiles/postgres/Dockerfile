FROM postgres:10.3-alpine 

ENV POSTGRES_PASSWORD=postgres
ENV POSTGRES_USER=postgres

COPY create-users.sql /docker-entrypoint-initdb.d/10-create-users.sql
COPY create-nats.sql  /docker-entrypoint-initdb.d/20-create-nss-db.sql



