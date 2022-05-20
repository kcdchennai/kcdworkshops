FROM ubuntu:focal-20220415

MAINTAINER Naveen Raman

RUN apt-get update
RUN apt-get install -y python2

ADD helloworld.py /home/helloworld.py

CMD ["/home/helloworld.py"]
ENTRYPOINT ["python2"]
