FROM mips64le/debian:12-slim

RUN apt update && apt install -y \
    nodejs \
    npm \
    && rm -rf /var/lib/apt/lists/*

RUN echo "Node.js version: $(node --version)" && echo "npm version: $(npm --version)"