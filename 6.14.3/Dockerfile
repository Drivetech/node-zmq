FROM node:6.14.4-alpine@sha256:6dd83754f5997b7222551d9842c4918a87e32dbf685cd201aef9367ca2d11a17

LABEL maintainer "Leonardo Gatica <lgatica@protonmail.com>"

RUN apk add --no-cache --virtual build-dependencies make gcc g++ python && \
  apk add --no-cache krb5-dev zeromq-dev && yarn global add node-gyp

CMD [ "node" ]
