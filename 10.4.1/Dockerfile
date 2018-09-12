FROM node:10.10.0-alpine@sha256:565dfb5f10143efd5f4c9df75a63d765adcd14b150fc61e5c1d54d70cb006e86

LABEL maintainer "Leonardo Gatica <lgatica@protonmail.com>"

RUN apk add --no-cache --virtual build-dependencies make gcc g++ python && \
  apk add --no-cache krb5-dev zeromq-dev && yarn global add node-gyp

CMD [ "node" ]
