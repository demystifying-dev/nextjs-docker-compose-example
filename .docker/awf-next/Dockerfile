FROM node:12-alpine

WORKDIR /usr/src/app

COPY ./app/package.json ./

RUN yarn

COPY ./app ./

EXPOSE 3000

CMD ["yarn", "dev"]
