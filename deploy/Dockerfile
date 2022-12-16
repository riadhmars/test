FROM debian:latest
RUN apt-get update -y && apt install -y python3 python3-pip && apt install python
RUN mkdir /data
COPY ~/test_smart/deploy /data
Workdir /data 
