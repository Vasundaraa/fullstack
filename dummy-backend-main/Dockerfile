FROM node:20

WORKDIR /app

COPY packages*.json ./

RUN npm install

COPY . .

EXPOSE 3000

CMD ["node", "dummy-backend.js"]