FROM node:4.9.1-alpine@sha256:41d0ad2557ea2a9e57e1a458c1d659e92f601586e07dcffef74c9cef542f6f6e

LABEL maintainer "Leonardo Gatica <lgatica@protonmail.com>"

RUN apk add --no-cache --virtual build-dependencies make gcc g++ python && \
  apk add --no-cache krb5-dev zeromq-dev && yarn global add node-gyp

CMD [ "node" ]
