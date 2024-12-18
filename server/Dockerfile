# Dockerfile
FROM node:lts-alpine

RUN mkdir /app
WORKDIR /app
COPY package*.json ./
RUN npm i
COPY index.js index.js

CMD npm start