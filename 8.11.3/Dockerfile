FROM node:8.14.1-alpine@sha256:dbe70ff383399ad9af341a44122700fece093ed4a2f794a88919caba59ba903e

LABEL maintainer "Leonardo Gatica <lgatica@protonmail.com>"

RUN apk add --no-cache --virtual build-dependencies make gcc g++ python && \
  apk add --no-cache krb5-dev zeromq-dev && yarn global add node-gyp

CMD [ "node" ]
