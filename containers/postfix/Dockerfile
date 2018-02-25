FROM kiall/kube-mx-base:latest

RUN apk add --no-cache postfix postfix-mysql postfix-pcre

COPY rootfs/ /

CMD /usr/local/bin/entrypoint
