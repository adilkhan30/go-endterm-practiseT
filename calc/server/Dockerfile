FROM golang

ADD . /go/src/

WORKDIR /app

COPY . /app

RUN go build -o app ./server

EXPOSE 4000

ENTRYPOINT  /app/app