FROM python:3.8.2-buster

RUN apt -y update \
 && apt -y upgrade \
 && apt clean \
 && rm -rf /var/lib/apt/lists/*

RUN pip install trac

