FROM node:4.8.3-alpine@sha256:f35eda806c796ba8c44fc9bcac263b5395e5c4eaac0e4487193c32c52839b500

LABEL maintainer "Leonardo Gatica <lgatica@protonmail.com>"

RUN apk add --no-cache --virtual build-dependencies make gcc g++ python && \
  apk add --no-cache krb5-dev

CMD [ "node" ]
