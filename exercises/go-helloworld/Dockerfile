FROM golang:alpine

COPY . /go/src/app

WORKDIR /go/src/app

ADD . .

RUN go build  -o helloworld

EXPOSE 6111

CMD ["./helloworld"]