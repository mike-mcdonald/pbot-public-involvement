FROM node:16

WORKDIR /home/node

ADD --chown=node:node package*.json .

RUN npm install

ADD --chown=node:node . .

CMD [ "npm", "run", "serve" ]
