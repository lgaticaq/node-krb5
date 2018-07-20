FROM node:8.11.1-alpine@sha256:89171382ea2e08a7ca84f653cd37e30e47b9c305baaee272899e25c912172f26

LABEL maintainer "Leonardo Gatica <lgatica@protonmail.com>"

RUN apk add --no-cache --virtual build-dependencies make gcc g++ python && \
  apk add --no-cache krb5-dev

CMD [ "node" ]
