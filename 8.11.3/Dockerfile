FROM node:8.11.3-alpine@sha256:c9f2470464363addb0be6a61678f44854e73eee974bbc792a71d4d2b7ffd5edd

LABEL maintainer "Leonardo Gatica <lgatica@protonmail.com>"

RUN apk add --no-cache --virtual build-dependencies make gcc g++ python && \
  apk add --no-cache krb5-dev zeromq-dev && yarn global add node-gyp

CMD [ "node" ]
