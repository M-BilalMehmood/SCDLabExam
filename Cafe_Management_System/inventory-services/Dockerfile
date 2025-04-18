FROM node:18-alpine

WORKDIR /usr/src/inventory-services

COPY package.json ./

RUN npm install

COPY . .

EXPOSE 3004

CMD ["npm", "start"]