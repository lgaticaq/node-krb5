FROM node:8.1.2-alpine@sha256:e50ac16fcaae4ddc29d7b0602178b42cfb5e13ad2888cc492c15ba6ff95ed689

LABEL maintainer "Leonardo Gatica <lgatica@protonmail.com>"

RUN apk add --no-cache --virtual build-dependencies make gcc g++ python && \
  apk add --no-cache krb5-dev

CMD [ "node" ]
