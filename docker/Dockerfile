FROM ubuntu:latest
LABEL maintainer="Robert Jensen robert@robert-jensen.dk"
LABEL description="Container to run dev-test-prod CI/CD Pipeline"
WORKDIR /tmp
RUN apt-get update && apt upgrade -y && apt install -y \ 
    curl \
    git \
    jq \
    wget \
    unzip 
#Create manual test files
#ADD setup.sh /tmp/setup.sh
#RUN chmod +x /tmp/setup.sh

