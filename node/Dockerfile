FROM node:alpine AS builder

WORKDIR /app

COPY . .

RUN npm install

EXPOSE 3000

CMD [ "node", "index.js" ]