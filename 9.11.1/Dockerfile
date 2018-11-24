FROM node:9.11.1-alpine@sha256:f8f6c69cce180a9a7c9fa685c86671b1e1f2ea7cc5f9a0dbe99d30cc7a0b6cbe

LABEL maintainer "Leonardo Gatica <lgatica@protonmail.com>"

RUN apk add --no-cache --virtual build-dependencies make gcc g++ python && \
  apk add --no-cache krb5-dev

CMD [ "node" ]
