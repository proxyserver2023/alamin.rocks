# Base Image
FROM python:3.8

# Disabling Python Output Buffering
# https://stackoverflow.com/questions/107705/disable-output-buffering
ENV PYTHONUNBUFFERED 1

RUN mkdir /app
WORKDIR /app
RUN mkdir src

COPY ./requirements.txt /app/requirements.txt
RUN pip install -r /app/requirements.txt
COPY ./src /app/src/

EXPOSE 8000