FROM ubuntu:xenial-20210416

RUN apt-get update && apt-get install -y --no-install-recommends \
                asciidoc \
                bash \
                build-essential \
                clang \
                cmake \
                elfutils \
                gcc-multilib \
                libb2-dev \
                libzstd1-dev \
                xsltproc \
        && rm -rf /var/lib/apt/lists/*
