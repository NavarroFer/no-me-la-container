FROM node:14

WORKDIR /usr/src/servidorhttp

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 9123

CMD [ "node", "ServidorHTTP.js" ]