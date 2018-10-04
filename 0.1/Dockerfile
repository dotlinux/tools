FROM ubuntu:latest

ADD config 〜/.ssh/
ADD sources.list /etc/apt/

RUN apt-key adv --recv-keys --keyserver subkeys.pgp.net 0x94C09C7F
RUN apt-get update && apt-get install -y tor curl telnet docker
RUN apt-get install -y connect-proxy
