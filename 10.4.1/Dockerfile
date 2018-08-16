FROM node:10.9.0-alpine@sha256:e9a83aa3e7ea576b93a21195f2e318ef8075ceccbebaa8f6c333294e9aa51dbd

LABEL maintainer "Leonardo Gatica <lgatica@protonmail.com>"

RUN apk add --no-cache --virtual build-dependencies make gcc g++ python && \
  apk add --no-cache krb5-dev zeromq-dev && yarn global add node-gyp

CMD [ "node" ]
