# REcker - an Ubuntu-based Docker image dedicated to malware reverse engineering

FROM ubuntu:rolling
WORKDIR /re
COPY . /re
RUN apt-get update && apt-get upgrade
RUN apt-get install -y inetsim git pip python3
