ARG PARENT_IMAGE=docker.io/library/ubuntu:24.04
FROM $PARENT_IMAGE

USER ubuntu
WORKDIR /home/ubuntu

ARG VERSION=1

RUN echo $PARENT_IMAGE > base.txt
RUN uname -a >> base.txt
RUN date >> base.txt
