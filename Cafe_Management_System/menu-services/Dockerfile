FROM node:18-alpine

WORKDIR /usr/src/menu-services

COPY package.json ./

RUN npm install

COPY . .

EXPOSE 3001

CMD ["npm", "start"]