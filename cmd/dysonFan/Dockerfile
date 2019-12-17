FROM python:3.8.0-buster

RUN pip install paho-mqtt
RUN pip install libpurecoollink
RUN apt-get update && apt-get install vim -y
RUN mkdir -p /dyson
COPY ./ /dyson
WORKDIR  /dyson 




