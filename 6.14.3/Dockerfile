FROM node:16.11.1-alpine@sha256:417b3856d2e5d06385123f3924c36f5735fb1f690289ca69f2ac9c35fd06c009

LABEL maintainer "Leonardo Gatica <lgatica@protonmail.com>"

RUN apk add --no-cache --virtual build-dependencies make gcc g++ python && \
  apk add --no-cache krb5-dev zeromq-dev && yarn global add node-gyp

CMD [ "node" ]
