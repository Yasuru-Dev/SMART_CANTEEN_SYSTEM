FROM node:18

WORKDIR /app

COPY backend/server/package.json ./

RUN npm install

COPY backend/server/ .

EXPOSE 5000

CMD ["node", "server.js"]