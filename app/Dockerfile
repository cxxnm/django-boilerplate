FROM python:3.11-buster

ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1

RUN apt-get update \
    && apt-get install -y libpq-dev

COPY requirements.txt /
RUN pip install --no-cache-dir -r /requirements.txt

WORKDIR /code/
COPY . .