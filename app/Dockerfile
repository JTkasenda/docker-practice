FROM node:13-alpine

ENV MONGO_INITDB_ROOT_USERNAME=admin \
    MONGO_INITDB_ROOT_PASSWORD=password

RUN mkdir -p /home/node-app

COPY . /home/node-app

CMD ["node", "/home/node-app/server.js"]