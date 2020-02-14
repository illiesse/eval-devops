FROM node:13.8.0-alpine

RUN mkdir -p /home/app/myreact
WORKDIR /home/app/myreact

COPY package*.json ./

EXPOSE 3000

RUN npm install
RUN npm install react-scripts@3.0.1 -g --silent

COPY . .

CMD [ "npm", "start"]