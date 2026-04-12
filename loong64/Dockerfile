FROM cr.loongnix.cn/library/debian:buster-slim

RUN apt-get update --allow-unauthenticated && apt-get install -y --no-install-recommends \
    ca-certificates \
    gnupg \
    && rm -rf /var/lib/apt/lists/*

RUN apt-get update --allow-unauthenticated && apt-get install -y --no-install-recommends \
    nodejs \
    npm \
    && rm -rf /var/lib/apt/lists/*

RUN echo "Node.js version: $(node --version)" && echo "npm version: $(npm --version)"
