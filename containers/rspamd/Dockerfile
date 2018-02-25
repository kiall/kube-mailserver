FROM kiall/kube-mx-base:latest

RUN apk add --no-cache rspamd rspamd-controller rspamd-proxy

COPY rootfs/ /

CMD /usr/local/bin/entrypoint
