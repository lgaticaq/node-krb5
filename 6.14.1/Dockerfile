FROM node:6.14.1-alpine@sha256:9280d82f5d32c228d23a632e87670c309847b7bf06cf1b4defe69c5588c25930

LABEL maintainer "Leonardo Gatica <lgatica@protonmail.com>"

RUN apk add --no-cache --virtual build-dependencies make gcc g++ python && \
  apk add --no-cache krb5-dev

CMD [ "node" ]
