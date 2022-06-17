FROM alpine
RUN apk add --no-cache curl wget busybox-extras netcat-openbsd mc bash
RUN pip install awscli
RUN apk --purge -v del wget
CMD tail -f /dev/null
