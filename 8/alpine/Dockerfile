FROM node:8-alpine

RUN apk --no-cache add --virtual native-deps \
  g++ gcc libgcc libstdc++ linux-headers make python && \
  npm install -g --silent protractor && \
  npm install -g --silent protractor-html-screenshot-reporter && \
  apk del make gcc g++ python libgcc libstdc++ linux-headers native-deps