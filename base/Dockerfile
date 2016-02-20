FROM alpine
MAINTAINER 'Aeon Builds <builds+dockerhub@aeon.io>'

RUN apk update \
 && apk upgrade \
 && apk add ca-certificates \
 && rm -rf /var/cache/apk/*
