# Containerised PKI
# (c)2019-2021, Karneliuk.com

FROM alpine:latest

LABEL maintainer="anton@karneliuk.com"
LABEL updated="2021-02-15"

RUN apk update; apk add openssl

RUN mkdir -p /opt/rootca; mkdir /opt/rootca/local; mkdir -p /opt/rootca/output
WORKDIR /opt/rootca

COPY run.sh /opt/run.sh