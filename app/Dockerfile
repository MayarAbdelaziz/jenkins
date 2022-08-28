FROM node:lts-alpine3.15

WORKDIR /app2

COPY package.json ./

RUN npm install

COPY . .

EXPOSE 800

CMD [ "node", "server.js" ]

