FROM node:20-alpine

ENV MONGO_DB_USERNAME=mongoadmin \
    MONGO_DB_PWD=secret

RUN mkdir -p /home/app

COPY ./app /home/app

WORKDIR /home/app

RUN npm install 

CMD ["node", "server.js"]
