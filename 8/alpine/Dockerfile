FROM node:8-alpine

ENV NODE_PATH /usr/local/lib/node_modules

RUN apk --no-cache add --virtual native-deps \
  g++ gcc libgcc libstdc++ linux-headers make python && \
  npm install -g --silent protractor && \
  npm install -g --silent protractor-jasmine2-screenshot-reporter && \
  npm install -g --silent node-rest-client && \
  npm install -g --silent node-rest-client-promise