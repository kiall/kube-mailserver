FROM kiall/kube-mx-base:latest

RUN apk add --no-cache clamav clamav-libunrar wget

COPY rootfs/ /

CMD /usr/local/bin/entrypoint
