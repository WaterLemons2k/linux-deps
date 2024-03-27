ARG DEBIAN_VERSION=buster
FROM debian:${DEBIAN_VERSION}-slim

RUN apt-get update && \
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
