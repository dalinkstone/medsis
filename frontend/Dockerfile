FROM oven/bun:1.3.2-alpine as base

WORKDIR /app

COPY package.json . 

RUN bun install

EXPOSE 3000

CMD ["bun", "dev"]
