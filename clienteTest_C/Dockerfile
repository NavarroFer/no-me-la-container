FROM node:14

WORKDIR /usr/src/cliente

COPY package*.json ./

RUN npm install

COPY . .

#CMD [ "node", "Cliente/Cliente_Interfaz.js" ]