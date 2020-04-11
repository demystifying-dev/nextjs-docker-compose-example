FROM node:12-alpine

# RUN mkdir -p /home/node/app/node_modules && chown -R node:node /home/node/app

# WORKDIR /home/node/app

WORKDIR /usr/src/app

COPY ./app/package.json ./

# USER node

RUN yarn

# COPY --chown=node:node ./app ./

COPY ./app ./

RUN yarn build

EXPOSE 3000

CMD ["yarn", "start"]
