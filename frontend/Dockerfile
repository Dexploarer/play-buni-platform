FROM oven/bun:1.0 as base
WORKDIR /app
COPY . .
RUN bun install
EXPOSE 3000
CMD ["bun", "run", "src/index.ts"]
