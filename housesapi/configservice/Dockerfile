FROM python:latest

ENV PYTHONUNBUFFERED 1
ENV PIP_ROOT_USER_ACTION=ignore

EXPOSE 8000

WORKDIR /configservice

COPY . /configservice

RUN pip install --upgrade pip && \
    pip install -r requirements.txt
