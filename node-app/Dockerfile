FROM node:14

WORKDIR /usr/src/app

COPY . .

RUN npm install

COPY . .

EXPOSE 3000

CMD ["node","server.js"]