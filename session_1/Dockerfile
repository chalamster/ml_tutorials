FROM ubuntu:18.04

RUN apt update

ENV DEBIAN_FRONTEND=noninteractive

# you can also add this to the first install - python3-numpy
RUN apt install -y python3 python3-pip \
	&& pip3 install numpy \
	&& pip3 install scipy \
	&& pip3 install pandas \
	&& pip3 install matplotlib \
	&& pip3 install jupyter

RUN apt install -y net-tools
