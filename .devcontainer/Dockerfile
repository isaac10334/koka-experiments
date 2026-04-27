FROM mcr.microsoft.com/devcontainers/base:ubuntu-24.04

RUN apt-get update \
 && apt-get install -y --no-install-recommends \
    build-essential \
    gcc \
    make \
    tar \
    curl \
    cmake \
    ninja-build \
    pkg-config \
 && rm -rf /var/lib/apt/lists/*

RUN curl -sSL https://github.com/koka-lang/koka/releases/latest/download/install.sh | sh

ENV PATH="/usr/local/bin:${PATH}"
