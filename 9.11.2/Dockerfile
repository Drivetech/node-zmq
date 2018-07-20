FROM node:9.11.2-alpine@sha256:5aa0756284c7f0222c2c16988fb58d6446427ac7ae8891aa50a2de721ef4191c

LABEL maintainer "Leonardo Gatica <lgatica@protonmail.com>"

RUN apk add --no-cache --virtual build-dependencies make gcc g++ python && \
  apk add --no-cache krb5-dev zeromq-dev && yarn global add node-gyp

CMD [ "node" ]
