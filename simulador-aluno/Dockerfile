FROM golang:1.16

WORKDIR /go/src

RUN apt-get update && \
    apt-get install build-essential librkafka-dev -y

CMD ["tail", "-f", "/dev/null"]
