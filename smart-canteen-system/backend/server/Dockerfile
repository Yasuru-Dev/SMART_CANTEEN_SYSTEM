FROM node:18

WORKDIR /app

# Copy package.json from correct path
COPY backend/server/package.json ./
COPY backend/server/package-lock.json ./

RUN npm install

# Copy all server files
COPY backend/server/ .

EXPOSE 5000

CMD ["node", "server.js"]