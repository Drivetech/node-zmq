FROM node:9.11.2-alpine@sha256:c812a92b98800c243bd4bafbc5a528b4fdf4bcd57a1d8de4192deded085ba6da

LABEL maintainer "Leonardo Gatica <lgatica@protonmail.com>"

RUN apk add --no-cache --virtual build-dependencies make gcc g++ python && \
  apk add --no-cache krb5-dev zeromq-dev && yarn global add node-gyp

CMD [ "node" ]
