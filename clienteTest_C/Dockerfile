FROM node:14

WORKDIR /usr/src/broker

COPY package*.json ./

RUN npm install

COPY . .

CMD [ "node", "broker.js" ]