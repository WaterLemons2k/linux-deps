ARG DEBIAN_VERSION=buster
FROM debian:${DEBIAN_VERSION}-slim

RUN echo 'deb http://archive.debian.org/debian buster main' >/etc/apt/sources.list && \
  apt-get update && \
  apt-get install -y --no-install-recommends \
  bc \
  bison \
  build-essential \
  ca-certificates \
  cpio \
  curl \
  debhelper \
  flex \
  git \
  kmod \
  libelf-dev \
  libssl-dev \
  lsb-release \
  lz4 \
  rsync \
  && rm -rf /var/lib/apt/lists/*
