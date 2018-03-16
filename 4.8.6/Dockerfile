FROM node:4.8.7-alpine@sha256:344b4b97a9a15f0ec20ffc9a6bd0465f3f80cde71e0f66c4dbf474de614716b8

LABEL maintainer "Leonardo Gatica <lgatica@protonmail.com>"

RUN apk add --no-cache --virtual build-dependencies make gcc g++ python && \
  apk add --no-cache krb5-dev

CMD [ "node" ]
