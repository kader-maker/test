FROM node:18.18-alpine

WORKDIR /Pluma-api
COPY package.json .
RUN npm install
COPY . .
CMD npm start
