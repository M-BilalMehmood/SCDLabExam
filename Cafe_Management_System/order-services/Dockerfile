FROM node:18-alpine

WORKDIR /usr/src/order-services

COPY package.json ./

RUN npm install

COPY . .

EXPOSE 3002

CMD ["npm", "start"]