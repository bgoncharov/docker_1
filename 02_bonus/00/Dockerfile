FROM ubuntu

MAINTAINER bogoncha <bogoncha@student.unit.ua>

RUN apt-get update && apt-get upgrade -y && apt-get install -y nodejs npm git vim emacs

RUN npm install yarn --global && npm install npm --global

# How to build it?
# docker build -t b00 .

# How to run it?
# docker run --rm -ti b00
