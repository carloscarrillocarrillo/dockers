FROM  node:buster

# Install Docker
RUN apt-get update 
RUN apt install docker.io -y
RUN docker --version

# FROM ubuntu:18.04

# Install AWS CLI
RUN apt-get install -y python3-pip
RUN pip3 install awscli
RUN aws --version

# RUN apt install -qqy curl
# RUN apt install apt-transport-https
# RUN apt install ca-certificates 
# RUN apt install -qqy gnupg-agent



# 
# RUN curl -fsSL https:/download.docker.com/linux/ubuntu/gpg | apt-key add -
# RUN apt-key fingerprint 0EBFCD88
# RUN add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"
# RUN apt-get update -y
# RUN apt-get install -y docker-ce docker-ce-cli containerd.io



# RUN  echo "deb http://archive.ubuntu.com/ubuntu vivid main universe\n" > /etc/apt/sources.list \
#   && echo "deb http://archive.ubuntu.com/ubuntu vivid-updates main universe\n" >> /etc/apt/sources.list
# RUN apt-get update
# RUN apt-get update && \
#     apt-get install -y software-properties-common && \
#     rm -rf /var/lib/apt/lists/*
#  RUN apt-get -qqy --no-install-recommends install software-properties-common 
# RUN apt-get -y --force-yes install software-properties-common 
# RUN curl -fsSL https://download.docker.com/linux/ubuntu/gpg | apt-key add -

# # RUN apt-get update -qqy \
# #   && apt-get -qqy --no-install-recommends install software-properties-common \
# #   && add-apt-repository -y ppa:git-core/ppa
# RUN add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu bionic stable"
# RUN apt install docker-ce