FROM alpine:latest

RUN apk update && \
    apk add bash python3 py3-pip git i2c-tools py3-smbus ttyd

CMD ["/usr/bin/ttyd", "-p", "8099", "bash"]