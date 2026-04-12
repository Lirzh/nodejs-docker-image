FROM cr.loongnix.cn/library/debian:buster-slim

RUN apt update && apt install -y \
    nodejs \
    npm \
    && rm -rf /var/lib/apt/lists/*

RUN echo "Node.js version: $(node --version)" && echo "npm version: $(npm --version)"