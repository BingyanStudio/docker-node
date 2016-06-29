FROM alpine:3.3

ENV NODE_VERSION 4.3.0

RUN apk update && \
    apk add 'nodejs<4.3.1' && \
    rm -rf /var/cache/apk/*

CMD ["node", "-i"]
