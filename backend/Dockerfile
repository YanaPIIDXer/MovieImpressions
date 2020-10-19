FROM golang:latest

RUN go get -u github.com/gin-gonic/gin

WORKDIR /go/src/server
ADD ./src /go/src/server

EXPOSE 3000

CMD ["go", "run", "main.go"]
