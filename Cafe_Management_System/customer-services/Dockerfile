FROM node:18-alpine

WORKDIR /usr/src/customer-services

COPY package.json ./

RUN npm install

COPY . .

EXPOSE 3005

CMD ["npm", "start"]