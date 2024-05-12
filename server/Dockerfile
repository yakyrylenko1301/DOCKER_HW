FROM alpine as server_img

LABEL maintainet="Yaroslav Kyrylenko"

ADD server.sh /server/

# Create app directory
WORKDIR /server/

RUN apk update && \
        apk add \
        net-tools \
        vim

RUN apk add --update --no-cache netcat-openbsd

