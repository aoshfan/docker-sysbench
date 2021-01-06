FROM debian:10.7-slim

MAINTAINER Aoshfan

RUN apt-get update && \
    apt-get install -y curl default-mysql-client

RUN curl -s https://packagecloud.io/install/repositories/akopytov/sysbench/script.deb.sh | bash

RUN apt-get clean
