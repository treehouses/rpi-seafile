
# Pull base image
FROM resin/rpi-raspbian:stretch
MAINTAINER hiroTochigi

# Install dependencies
RUN apt-get update && apt-get install -y \
    python \
    python-dev \
    python-pip \
    python-virtualenv \
    --no-install-recommends && \
    rm -rf /var/lib/apt/lists/*

# Define default command
CMD ["bash"]
