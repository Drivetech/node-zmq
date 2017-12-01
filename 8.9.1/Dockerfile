FROM node:8.9.1-alpine@sha256:b7f30d8810a8e10bd34cc12995c79dcdad81cd99c5ad6cfd0597e02683954de0

LABEL maintainer "Leonardo Gatica <lgatica@protonmail.com>"

RUN apk add --no-cache --virtual build-dependencies make gcc g++ python && \
  apk add --no-cache krb5-dev zeromq-dev && yarn global add node-gyp

CMD [ "node" ]
