FROM node:18-slim AS build

WORKDIR /frontend
COPY package.json .
COPY build ./build
ENV PORT=5000
EXPOSE 5000

ENTRYPOINT ["node", "build/index.js" ]