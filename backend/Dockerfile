FROM golang:1.25.4 AS build

WORKDIR /app

COPY main.go .
COPY go.mod .

RUN CGO_ENABLED=0 GOOS=linux go build -o /app/backend .

FROM scratch

COPY --from=build /app/backend .

CMD ["./backend"]
