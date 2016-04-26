FROM ubuntu:latest

RUN apt-get update && apt-get install -y git python  libssl-dev --fix-missing

RUN apt-get install -y software-properties-common git
RUN apt-add-repository -y ppa:ansible/ansible
RUN apt-get update
RUN apt-get install -y ansible
