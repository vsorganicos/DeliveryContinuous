FROM ubuntu:latest

RUN apt-get update && apt-get install -y git python libssl-dev wget --fix-missing
RUN apt-get install -y software-properties-common git
RUN apt-add-repository -y ppa:ansible/ansible
RUN apt-get update
RUN apt-get install -y ansible
RUN wget -v -O /tmp/get-pip.py https://bootstrap.pypa.io/get-pip.py
RUN python /tmp/get-pip.py
WORKDIR /root/
COPY . /root/vsorganicos-database
ENV TERM dumb
