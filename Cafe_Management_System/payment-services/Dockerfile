FROM node:18-alpine

WORKDIR /usr/src/payment-services

COPY package.json ./

RUN npm install

COPY . .

EXPOSE 3003

CMD ["npm", "start"]