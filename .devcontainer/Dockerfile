FROM ubuntu:20.04

ENV DEBIAN_FRONTEND=noninteractive

RUN apt-get update \
 && apt-get install -y --no-install-recommends \
    git \
    build-essential \
    cmake \
    gdb \
 && apt-get -y clean \
 && rm -rf /var/lib/apt/lists/*
