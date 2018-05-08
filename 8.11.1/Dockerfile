FROM node:8.11.1-alpine@sha256:dcee83ad53ab1d2754ca7029a06aa1f2c79bf3ee08b1a40bb052443efacd3b8f

LABEL maintainer "Leonardo Gatica <lgatica@protonmail.com>"

RUN apk add --no-cache --virtual build-dependencies make gcc g++ python && \
  apk add --no-cache krb5-dev zeromq-dev && yarn global add node-gyp

CMD [ "node" ]
