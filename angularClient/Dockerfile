FROM node:10.13

ENV NODE_VERSION 10.13.0

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

COPY . ./

EXPOSE 4200

CMD [ "npm", "start" ]
