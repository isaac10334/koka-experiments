FROM mcr.microsoft.com/devcontainers/base:ubuntu-24.04

RUN curl -sSL https://github.com/koka-lang/koka/releases/latest/download/install.sh | sh \
 && echo 'export PATH="$HOME/.koka/bin:$PATH"' >> /etc/profile.d/koka.sh
