FROM golang:1.25.4 AS build

WORKDIR /app

COPY main.go .
COPY go.mod .

RUN CGO_ENABLED=0 GOOS=linux go build -o /app/backend .

FROM scratch

WORKDIR /app

COPY --chown=app:app --from=build /app/backend .

EXPOSE 8080

CMD ["/app/backend"]
