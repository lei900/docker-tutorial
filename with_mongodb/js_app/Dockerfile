FROM node:18-alpine3.15

ENV MONGO_DB_USERNAME=admin \
    MONGO_DB_PWD=password

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

CMD ["node", "server.js"]
