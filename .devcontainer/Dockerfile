FROM mcr.microsoft.com/devcontainers/universal:2-linux

RUN apt-get update
RUN pip install django

#RUN sudo apt-get -y install gnupg curl | \
    #curl -fsSL https://www.mongodb.org/static/pgp/server-7.0.asc | \
    #gpg -o /usr/share/keyrings/mongodb-server-7.0.gpg --dearmor | \
    #echo "deb [ arch=amd64,arm64 ] https://repo.mongodb.org/apt/ubuntu focal/mongodb-org/4.4 multiverse" | \
    #tee /etc/apt/sources.list.d/mongodb-org-4.4.list | \
    #apt update | \
RUN apt -y install mongodb
