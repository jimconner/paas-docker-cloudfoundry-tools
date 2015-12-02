FROM golang:1.5.1-alpine

RUN apk update
RUN apk add git
RUN go get github.com/geofffranks/spruce

ENTRYPOINT [ "spruce" ]