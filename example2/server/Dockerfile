FROM ubuntu

RUN apt-get install -y python3

WORKDIR /usr/src/app/

COPY hello.txt /usr/src/app/

CMD python3 -m http.server
