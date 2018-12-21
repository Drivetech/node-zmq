FROM node:6.15.1-alpine@sha256:4715af5097c04ba3e3923bac769e67ec16eb7f37f43f430f56fa03c8e3c32878

LABEL maintainer "Leonardo Gatica <lgatica@protonmail.com>"

RUN apk add --no-cache --virtual build-dependencies make gcc g++ python && \
  apk add --no-cache krb5-dev zeromq-dev && yarn global add node-gyp

CMD [ "node" ]
