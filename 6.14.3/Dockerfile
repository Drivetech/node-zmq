FROM node:6.14.3-alpine@sha256:5a00752aeffa1efb61faca9c12e45d7a29ffa5ebcdb63ecd26e38eac974e68cd

LABEL maintainer "Leonardo Gatica <lgatica@protonmail.com>"

RUN apk add --no-cache --virtual build-dependencies make gcc g++ python && \
  apk add --no-cache krb5-dev zeromq-dev && yarn global add node-gyp

CMD [ "node" ]
