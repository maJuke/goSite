FROM golang:1.24.4

WORKDIR /app

COPY go.mod go.sum ./
RUN go mod download

COPY . .

RUN go build -o main .

RUN ls -l /app

CMD ["/app/main"]
