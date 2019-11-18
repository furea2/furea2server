FROM python:3.7

MAINTAINER furea2

ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1

RUN mkdir /server
WORKDIR /server

COPY requirements.txt /server/

RUN python -m pip install --upgrade pip
RUN python -m pip install -r requirements.txt

COPY . /server/