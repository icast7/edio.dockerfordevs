FROM debian:10-slim

COPY . .

RUN apt-get update -y && apt-get upgrade -y && apt-get dist-upgrade -y
RUN apt-get install -y php

# docker build . -t copybefore