FROM alpine as client_img

LABEL maintainet="Yaroslav Kyrylenko"

ADD client.sh /client/
# Create app directory
WORKDIR /client/

RUN apk update && \
        apk add \
        net-tools \
        vim

RUN apk add --update --no-cache netcat-openbsd
