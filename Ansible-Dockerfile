FROM ubuntu:20.04
RUN apt update
RUN apt upgrade -y
RUN apt install git python3 python3-pip -y
RUN pip3 install ansible
RUN mkdir /opt/ansible
WORKDIR /opt/ansible
