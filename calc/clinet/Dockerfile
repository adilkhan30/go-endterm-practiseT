FROM golang

ADD . /go/src/

WORKDIR /app

COPY . /app

RUN go build -o app /client

EXPOSE 4000

ENTRYPOINT  /app/app