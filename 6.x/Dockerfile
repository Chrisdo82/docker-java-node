FROM java:8

MAINTAINER Christian Dornbusch <christian.dornbusch@useeds.de>

# Global install nodejs
RUN apt-get update && apt-get install -y curl apt-transport-https && \
    curl -sL https://deb.nodesource.com/setup_6.x | bash && \
    apt-get install -y nodejs build-essential

WORKDIR /workspace