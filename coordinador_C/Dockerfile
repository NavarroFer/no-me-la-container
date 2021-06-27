FROM node:14

WORKDIR /usr/src/coordinador

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 1234

CMD [ "node", "Coordinador.js" ]