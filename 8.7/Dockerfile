FROM node:8.7

MAINTAINER Christian Dornbusch <christian.dornbusch@useeds.de>

# Global install nodejs
RUN curl -sL https://deb.nodesource.com/setup_8.7 | sudo -E bash - && \
    sudo apt-get install -y nodejs build-essential

WORKDIR /workspace
