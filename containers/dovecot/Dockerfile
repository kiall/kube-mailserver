FROM kiall/kube-mx-base:latest

RUN apk add --no-cache dovecot dovecot-mysql dovecot-pigeonhole-plugin dovecot-pigeonhole-plugin-extdata

COPY rootfs/ /

CMD /usr/local/bin/entrypoint
