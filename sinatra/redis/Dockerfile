FROM ubuntu:14.04
RUN apt-get -yqq update 
RUN apt-get -yqq install redis-server redis-tools
EXPOSE 6379
ENTRYPOINT [ "/usr/bin/redis-server" ]
CMD []
