FROM node:6.14.3-alpine@sha256:ab6b240e933a77232bea533169a0350beabc0cc070e6c51fa4fbdef7dd2e3e0c

LABEL maintainer "Leonardo Gatica <lgatica@protonmail.com>"

RUN apk add --no-cache --virtual build-dependencies make gcc g++ python && \
  apk add --no-cache krb5-dev zeromq-dev && yarn global add node-gyp

CMD [ "node" ]
