FROM node:13.8.0-alpine

RUN mkdir -p /home/app/api
WORKDIR /home/app/api

COPY package*.json ./

EXPOSE 5000

RUN npm install

COPY . .

CMD [ "npm", "start"]