FROM node:9.2.0-alpine@sha256:e174cb4f00bd5aacfe798ad7ee6c2985adceade4f487a9532de2ce8a067f7365

LABEL maintainer "Leonardo Gatica <lgatica@protonmail.com>"

RUN apk add --no-cache --virtual build-dependencies make gcc g++ python && \
  apk add --no-cache krb5-dev zeromq-dev && yarn global add node-gyp

CMD [ "node" ]
