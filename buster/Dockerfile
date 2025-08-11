ARG DEBIAN_VERSION=buster
FROM debian:${DEBIAN_VERSION}-slim

RUN sed -i 's/deb.d/archive.d/g' /etc/apt/sources.list && \
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
