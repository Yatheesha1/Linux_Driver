#Create ubuntu as base image
FROM ubuntu

#Install packages
RUN apt-get -y update \
    && apt-get -y install sudo \
    && apt-get -y install vim \
    && apt-get -y install make \
    && apt-get -y install software-properties-common \
    && add-apt-repository ppa:deadsnakes/ppa \
    && apt-get -y install python3.7