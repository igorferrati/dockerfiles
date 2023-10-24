FROM ubuntu:22.04

RUN apt-get update && apt-get install -y \
    vim \
    docker.io \
    && apt-get clean

RUN curl -fsSL -o get_helm.sh https://raw.githubusercontent.com/helm/helm/master/scripts/get-helm-3 \
    && chmod +x get_helm.sh \
    && ./get_helm.sh

RUN apt-get install -y python3 python3-pip \
    && apt-get clean

