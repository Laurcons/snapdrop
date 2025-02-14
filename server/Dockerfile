FROM node:alpine

WORKDIR /home/node/app

COPY *.json .
COPY index.js .

RUN npm i

ENTRYPOINT ["npm", "run", "start"]