FROM node:16

WORKDIR /usr/src/app

COPY src/backend/package*.json ./

RUN npm install

COPY src/backend/ .

EXPOSE 8080

CMD ["node", "server.js"]