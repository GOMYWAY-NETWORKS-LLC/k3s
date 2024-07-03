# Docker image for building the Go app
FROM golang:1.22.4

WORKDIR /app
ADD . /app

RUN GO111MODULE=on go mod download
