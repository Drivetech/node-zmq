FROM node:6.14.3-alpine@sha256:c989015fbdea52f1775803843d3a784f62e212e76259a52f572d0e460d47fda8

LABEL maintainer "Leonardo Gatica <lgatica@protonmail.com>"

RUN apk add --no-cache --virtual build-dependencies make gcc g++ python && \
  apk add --no-cache krb5-dev zeromq-dev && yarn global add node-gyp

CMD [ "node" ]
