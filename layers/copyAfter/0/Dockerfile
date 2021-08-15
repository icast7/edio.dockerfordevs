FROM debian:10-slim

RUN apt-get update -y && apt-get upgrade -y && apt-get dist-upgrade -y
RUN apt-get install -y php

COPY . .
# docker build . -t copyafter