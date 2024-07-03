# Docker image for building the Go app
FROM golang:1.22.5

WORKDIR /app
ADD . /app

RUN GO111MODULE=on go mod download
