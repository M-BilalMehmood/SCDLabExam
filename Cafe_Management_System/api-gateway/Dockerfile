FROM node:18-alpine

WORKDIR /usr/src/api-gateway

COPY package.json ./

RUN npm install

COPY . .

EXPOSE 3000

CMD ["npm", "start"]