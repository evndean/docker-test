FROM ubuntu:14.04
MAINTAINER "Evan Dean"
RUN apt-get update && \
    apt-get install -y apache2
CMD service apache2 start &&\
    while true; do sleep 60; done
