FROM node:12-alpine

RUN mkdir -p /usr/src/app 

WORKDIR /usr/src/app

COPY ./app/package.json /usr/src/app/

RUN yarn

EXPOSE 3000

CMD ["yarn", "dev"]
