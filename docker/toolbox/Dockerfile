FROM ubuntu:focal
RUN apt update
RUN apt install -y curl wget python pip  && \
    pip install awscli
RUN apt purge pip
RUN apt install -y htop
CMD tail -f /dev/null
