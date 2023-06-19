FROM node:8.17.0-alpine@sha256:c8456a06563920080bdc01715626c1be8211edc8cd18f34f15e1b7b936e30746

LABEL maintainer "Leonardo Gatica <lgatica@protonmail.com>"

RUN apk add --no-cache --virtual build-dependencies make gcc g++ python && \
  apk add --no-cache krb5-dev zeromq-dev && yarn global add node-gyp

CMD [ "node" ]
