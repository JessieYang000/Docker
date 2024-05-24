FROM node:14

WORKDIR /app

COPY pakage.json .

RUN npm install

COPY . .

EXPOSE 80

CMD [ "node", "server.js" ]