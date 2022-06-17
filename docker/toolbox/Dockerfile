FROM alpine
RUN apk add --no-cache curl busybox-extras netcat-openbsd python3 py3-pip && \
pip install awscli
RUN apk --purge -v del wget
CMD tail -f /dev/null
