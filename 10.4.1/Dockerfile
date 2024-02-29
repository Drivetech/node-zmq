FROM node:10.24.1-alpine@sha256:02767d92553e465bf51e0bd661074f2e70bd575c4a69a0d610aa6e78fd20a9bf

LABEL maintainer "Leonardo Gatica <lgatica@protonmail.com>"

RUN apk add --no-cache --virtual build-dependencies make gcc g++ python && \
  apk add --no-cache krb5-dev zeromq-dev && yarn global add node-gyp

CMD [ "node" ]
