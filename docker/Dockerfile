FROM oven/bun:latest

ENV NODE_PATH=/node_modules
WORKDIR /app
VOLUME "/app"
RUN bun install \
        tailwindcss@latest \
        @tailwindcss/forms \
        @tailwindcss/typography \
    && mv node_modules /

ENTRYPOINT ["bunx", "tailwindcss"]
