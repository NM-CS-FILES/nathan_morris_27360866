FROM mcr.microsoft.com/devcontainers/universal:2-linux

RUN apt-get update
RUN pip install django

RUN echo "deb [ arch=amd64,arm64 ] https://repo.mongodb.org/apt/ubuntu focal/mongodb-org/4.4 multiverse" | \
    sudo tee /etc/apt/sources.list.d/mongodb-org-4.4.list | \
    sudo apt update | \
    sudo apt install mongodb-org
