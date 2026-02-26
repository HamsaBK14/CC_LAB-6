FROM alpine:latest

RUN apk add --no-cache g++

WORKDIR /app

COPY app.cpp .

RUN g++ app.cpp -o app

CMD ["./app"]