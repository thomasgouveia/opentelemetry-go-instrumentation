FROM golang:1.21.3
WORKDIR /sample-app
COPY . .
RUN go mod init go.opentelemetry.io/auto/internal/test/e2e/nethttp && go mod tidy && go build -o main
