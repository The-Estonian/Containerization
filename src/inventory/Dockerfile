FROM node:20-alpine

WORKDIR /usr/src/

COPY package*.json ./

RUN npm install --no-cache

COPY . .

EXPOSE 3000

CMD ["node", "server.js"]
