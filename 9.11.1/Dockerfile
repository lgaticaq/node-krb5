FROM node:9.11.1-alpine@sha256:ec1bc675cbcb0c5215af40c7c1b7a8ea9d5f17b084eaf7b4b4e69e0963a38f26

LABEL maintainer "Leonardo Gatica <lgatica@protonmail.com>"

RUN apk add --no-cache --virtual build-dependencies make gcc g++ python && \
  apk add --no-cache krb5-dev

CMD [ "node" ]
