FROM node:8

WORKDIR /home/node/app
COPY package*.json ./

# RUN apk add --no-cache \
# libc6-compat g++

RUN yarn install

COPY . .

ENV NPM_CONFIG_LOGLEVEL info
EXPOSE 3000

CMD yarn start
