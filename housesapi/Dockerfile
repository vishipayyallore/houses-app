FROM python:latest

ENV PYTHONUNBUFFERED 1
ENV PIP_ROOT_USER_ACTION=ignore

WORKDIR /housesapi

COPY requirements.txt /housesapi/requirements.txt
RUN pip install --upgrade pip
RUN pip install -r requirements.txt

COPY . /housesapi