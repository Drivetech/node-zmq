FROM node:19.9.0-alpine@sha256:0e9961345f0ef2ea3e132990e814a26cb9fa8f89e50abb68751c6bc45ca014c4

LABEL maintainer "Leonardo Gatica <lgatica@protonmail.com>"

RUN apk add --no-cache --virtual build-dependencies make gcc g++ python && \
  apk add --no-cache krb5-dev zeromq-dev && yarn global add node-gyp

CMD [ "node" ]
