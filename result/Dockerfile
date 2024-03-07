FROM node:20-alpine AS builder
WORKDIR  /result
COPY . .
RUN npm install
EXPOSE 80
CMD node server.js