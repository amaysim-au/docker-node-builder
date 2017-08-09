FROM node:8-alpine

RUN apk --no-cache add --virtual native-deps \
  g++ gcc libgcc libstdc++ linux-headers make python && \
  npm install -g --silent protractor && \
  npm install -g --silent protractor-jasmine2-screenshot-reporter