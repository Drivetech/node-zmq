FROM node:10.4.1-alpine@sha256:2cda73dd26369c2ec69130ddda6f83ff4980fd6fc8e73b5e670a7670d4c86ba0

LABEL maintainer "Leonardo Gatica <lgatica@protonmail.com>"

RUN apk add --no-cache --virtual build-dependencies make gcc g++ python && \
  apk add --no-cache krb5-dev zeromq-dev && yarn global add node-gyp

CMD [ "node" ]
