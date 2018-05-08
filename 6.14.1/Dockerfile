FROM node:6.14.1-alpine@sha256:7beb52c982ca7caa3ee4d69d2a4af6fea1dd20f9db52dbbea0635ed696c6a57a

LABEL maintainer "Leonardo Gatica <lgatica@protonmail.com>"

RUN apk add --no-cache --virtual build-dependencies make gcc g++ python && \
  apk add --no-cache krb5-dev zeromq-dev && yarn global add node-gyp

CMD [ "node" ]
