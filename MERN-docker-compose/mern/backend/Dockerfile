FROM node:18.9.1

WORKDIR  /app

ADD package.json  .

RUN npm install

ADD . .

CMD ["npm", "start"]
