FROM python:latest

ENV PYTHONUNBUFFERED 1
ENV PIP_ROOT_USER_ACTION=ignore

EXPOSE 8000

WORKDIR /housesapi

COPY . /housesapi

RUN pip install --upgrade pip && \
    pip install -r requirements.txt

# CMD ["python", "./config/manage.py", "runserver", "0.0.0.0:8000"]

WORKDIR /housesapi/config