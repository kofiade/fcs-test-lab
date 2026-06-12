# Using an older base image to trigger image scan findings
FROM ubuntu:18.04

RUN apt-get update && apt-get install -y \
    curl \
    wget \
    openssl

WORKDIR /app
COPY . .

CMD ["/bin/bash"]
