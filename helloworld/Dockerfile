FROM ubuntu

MAINTAINER Naveen Raman

RUN apt-get update
RUN apt-get install -y python2

ADD hello.py /home/hello.py

CMD ["/home/hello.py"]
ENTRYPOINT ["python2"]
