FROM node:6.11.0-alpine@sha256:3e809c8dd79e3e5a5fbdf9099a7a482a019f8739da7fb0a8400de6a6439deb4b

LABEL maintainer "Leonardo Gatica <lgatica@protonmail.com>"

RUN apk add --no-cache --virtual build-dependencies make gcc g++ python && \
  apk add --no-cache krb5-dev

CMD [ "node" ]
