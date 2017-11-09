FROM node:8-alpine

ENV NODE_PATH /usr/local/lib/node_modules

RUN apk --no-cache add --virtual native-deps \
  g++ gcc libgcc libstdc++ linux-headers make python curl && \
  npm install -g --silent protractor && \
  npm install -g --silent protractor-jasmine2-screenshot-reporter && \
  npm install -g --silent jasmine-spec-reporter && \
  npm install -g --silent protractor-console-plugin && \
  npm install -g --silent node-rest-client && \
  npm install -g --silent node-rest-client-promise && \
  npm install -g --silent wdio-jasmine-framework && \
  npm install -g --silent wdio-screenshot && \
  npm install -g --silent wdio-junit-reporter && \
  npm install -g --silent wdio-spec-reporter && \
  npm install -g --silent webdriverio && \
  npm install -g --silent dotenv