# The last Debian with gcc-4.9-base version 4.9.2-10+deb8u1 (wanted by gcc-4.9)
ARG DEBIAN_VERSION=jessie-20181112
FROM debian:${DEBIAN_VERSION}-slim

RUN echo 'deb http://archive.debian.org/debian jessie main' >/etc/apt/sources.list && \
  apt-get update && \
  apt-get install -y --allow-unauthenticated --no-install-recommends \
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
  rsync && \
  rm -rf /var/lib/apt/lists/*
