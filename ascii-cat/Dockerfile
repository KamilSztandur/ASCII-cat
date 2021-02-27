FROM ubuntu:latest
MAINTAINER Kamil Sztandur <kamil.sztandur@vp.pl>

RUN apt-get update && \
    apt-get clean

ADD * /

CMD chmod a+x launch && \
    ./launch 
