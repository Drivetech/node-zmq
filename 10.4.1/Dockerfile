FROM node:10.24.1-alpine@sha256:dc98dac24efd4254f75976c40bce46944697a110d06ce7fa47e7268470cf2e28

LABEL maintainer "Leonardo Gatica <lgatica@protonmail.com>"

RUN apk add --no-cache --virtual build-dependencies make gcc g++ python && \
  apk add --no-cache krb5-dev zeromq-dev && yarn global add node-gyp

CMD [ "node" ]
