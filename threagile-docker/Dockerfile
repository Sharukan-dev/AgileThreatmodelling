FROM golang:1.22-alpine

RUN apk add --no-cache git

RUN go install github.com/threagile/threagile@latest

WORKDIR /app
ENTRYPOINT ["threagile"]
