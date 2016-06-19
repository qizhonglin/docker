FROM ubuntu:14.04

RUN apt-get -yqq update  
RUN apt-get -yqq install ruby 
RUN apt-get -yqq install ruby-dev 
RUN apt-get -yqq install build-essential 
RUN apt-get -yqq install redis-tools
RUN gem install --no-rdoc --no-ri sinatra json redis

RUN mkdir -p /opt/webapp

EXPOSE 4567

CMD [ "/opt/webapp/bin/webapp" ]


