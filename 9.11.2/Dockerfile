FROM node:9.11.2-alpine@sha256:ba6622980a99d360f10a32bcc4290d27f5284117392defe184976deb7fbbb055

LABEL maintainer "Leonardo Gatica <lgatica@protonmail.com>"

RUN apk add --no-cache --virtual build-dependencies make gcc g++ python && \
  apk add --no-cache krb5-dev zeromq-dev && yarn global add node-gyp

CMD [ "node" ]
