FROM node:8-alpine

ENV NODE_PATH /usr/local/lib/node_modules

RUN apk --no-cache add --virtual native-deps \
  g++ gcc libgcc libstdc++ linux-headers make python curl && \
  npm install -g --silent protractor@5.1.2 && \
  npm install -g --silent protractor-jasmine2-screenshot-reporter@0.4.2 && \
  npm install -g --silent node-rest-client@3.1.0 && \
  npm install -g --silent node-rest-client-promise@3.0.0 && \
  npm install -g --silent dotenv@4.0.0