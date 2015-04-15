FROM ubuntu

RUN apt-get install -y curl

CMD /bin/bash -c "while true; do curl -s http://server:8000/hello.txt; sleep 2s; done"
