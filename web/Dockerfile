FROM python:3.5
ENV PYTHONUNBUFFERED 1
RUN mkdir /code
WORKDIR /code
ADD requirements.txt /code/
RUN pip install -r requirements.txt

# RUN mkdir /usr/src/app

# WORKDIR /usr/src/app
RUN mkdir /log

ADD . /code/