# Use an official Node.js image as the base image
FROM ubuntu:latest

RUN apt-get update
RUN apt-get install -y iputils-ping

RUN apt install -y openssh-client 

RUN apt install -y openssl

# That would just copy the whole file
COPY ./linux/github-connect.pem github-connect.pem

RUN chmod 0400 github-connect.pem

