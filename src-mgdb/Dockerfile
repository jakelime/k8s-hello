ARG url_docker=artifact.stengglink.com:34000
FROM ${url_docker}/mongodb/mongodb-community-server:8.0.15-ubi9

WORKDIR /opt/mongodb_init
COPY init-db.js .
