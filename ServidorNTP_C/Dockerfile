FROM node:14

WORKDIR /usr/src/servidorNTP

RUN npm install

COPY . .

EXPOSE 4444

CMD [ "node", "ServidorNTP.js" ]