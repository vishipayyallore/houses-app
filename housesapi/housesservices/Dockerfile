FROM python:latest

ENV PYTHONUNBUFFERED 1
ENV PIP_ROOT_USER_ACTION=ignore

WORKDIR /configservice

COPY . /configservice

RUN pip install --upgrade pip && \
    pip install -r requirements.txt

# Run database migrations
CMD ["python", "manage.py", "migrate"]