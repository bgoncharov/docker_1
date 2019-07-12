FROM ubuntu

MAINTAINER bogoncha "bogoncha@students.42.us.org"

RUN apt-get update && apt-get install -y cowsay fortune lolcat

ENTRYPOINT /usr/games/fortune | /usr/games/cowsay | /usr/games/lolcat
