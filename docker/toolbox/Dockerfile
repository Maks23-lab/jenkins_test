FROM alpine
RUN apk add --no-cache curl wget busybox-extras netcat-openbsd python3 py-pip postgresql_client && \
    pip install awscli && apk --purge -v del py-pip
CMD tail -f /dev/null
