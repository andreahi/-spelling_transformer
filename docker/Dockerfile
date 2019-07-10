FROM tensorflow/tensorflow:2.0.0b1-gpu-py3

WORKDIR /app
COPY requirements.txt /app

RUN apt-get update
RUN pip3 install -r requirements.txt
