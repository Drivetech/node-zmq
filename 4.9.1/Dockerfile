FROM node:18.9.0-alpine@sha256:1cdf154f10cf19a7eac49b44bce405791e0dc972484ec4a9c3d18cb75938999e

LABEL maintainer "Leonardo Gatica <lgatica@protonmail.com>"

RUN apk add --no-cache --virtual build-dependencies make gcc g++ python && \
  apk add --no-cache krb5-dev zeromq-dev && yarn global add node-gyp

CMD [ "node" ]
