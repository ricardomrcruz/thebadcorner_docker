FROM node:20.9.0-alpine3.17

WORKDIR /app

COPY package*.json ./

RUN npm i

COPY src ./src
COPY .env /app/.env
COPY tsconfig.json ./tsconfig.json


CMD npm start