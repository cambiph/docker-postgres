FROM mdillon/postgis:9.6-alpine
#FROM postgres:11-alpine

ENV POSTGRES_USER=build
ENV POSTGRES_PASSWORD=build

ADD init.sql /docker-entrypoint-initdb.d/
