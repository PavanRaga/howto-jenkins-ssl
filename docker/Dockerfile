FROM ubuntu:14.04

RUN apt-get update -y
RUN apt-get install -y git bash-completion dnsutils nginx telnet lsof
RUN git clone https://github.com/certbot/certbot.git
RUN cd certbot && ./letsencrypt-auto --help

EXPOSE 443
# WORKDIR ~

CMD bash

