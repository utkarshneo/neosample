FROM node:12-alpine

RUN src/app

WORKDIR /src/app
COPY package*.json ./

USER node