FROM ubuntu:20.04

ENV DEBIAN_FRONTEND=noninteractive

RUN apt-get update && apt-get install -y \
    build-essential \
    git \
    dkms \
    linux-headers-generic \
    curl \
    wget \
    unzip \
    sudo \
    gcc \
    make \
    ca-certificates \
    && rm -rf /var/lib/apt/lists/*
