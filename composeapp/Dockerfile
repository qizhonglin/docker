FROM python:2.7

ADD . /composeapp

WORKDIR /composeapp

RUN pip --proxy http://165.225.96.34:10015 install -r requirements.txt
