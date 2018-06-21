FROM node:10.5.0-alpine@sha256:21b58de0d309e8b793fb508e610762e522074a3bd5bef6f3ff74b7bade338aec

LABEL maintainer "Leonardo Gatica <lgatica@protonmail.com>"

RUN apk add --no-cache --virtual build-dependencies make gcc g++ python && \
  apk add --no-cache krb5-dev zeromq-dev && yarn global add node-gyp

CMD [ "node" ]
