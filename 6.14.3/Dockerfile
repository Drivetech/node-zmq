FROM node:6.17.1-alpine@sha256:ac775e5c37b78443690a840b22973dd5a60ff2cc17ecd1d3921a45e831071d61

LABEL maintainer "Leonardo Gatica <lgatica@protonmail.com>"

RUN apk add --no-cache --virtual build-dependencies make gcc g++ python && \
  apk add --no-cache krb5-dev zeromq-dev && yarn global add node-gyp

CMD [ "node" ]
