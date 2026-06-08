FROM node:18

WORKDIR /app

COPY backend/package.json ./

RUN npm install

COPY backend/server/ .

EXPOSE 5000

CMD ["node", --experimental-global-webcrypto server.js"]