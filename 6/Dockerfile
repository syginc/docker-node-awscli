FROM node:6

RUN apt-get update && \
    apt-get install -y python3-pip && \
    pip3 install --upgrade --user awscli && \
    rm -rf /var/lib/apt/lists/*
