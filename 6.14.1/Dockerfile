FROM node:6.14.4-alpine@sha256:e9f69716044840be97aca80dae7dee0efd126e8043623478de9ab9bc19badccd

LABEL maintainer "Leonardo Gatica <lgatica@protonmail.com>"

RUN apk add --no-cache --virtual build-dependencies make gcc g++ python && \
  apk add --no-cache krb5-dev

CMD [ "node" ]
