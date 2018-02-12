FROM python:3
ENV PYTHONUNBUFFERED 1
RUN mkdir /backoffice
WORKDIR /backoffice
ADD requirements.txt /backoffice/
RUN pip install -r requirements.txt
ADD . /backoffice/