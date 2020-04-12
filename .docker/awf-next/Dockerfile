FROM node:12-alpine

RUN mkdir -p /usr/src/app 

WORKDIR /usr/src/app

COPY ./app/package.json /usr/src/app/

RUN yarn

#COPY ./app /usr/src/app/

EXPOSE 3000

RUN pwd

RUN ls -la

CMD ["yarn", "dev"]
