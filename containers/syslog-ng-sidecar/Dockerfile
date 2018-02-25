FROM kiall/kube-mx-base:latest

RUN apk add --no-cache syslog-ng

COPY rootfs/ /

CMD ["/usr/sbin/syslog-ng", "-F", "-f", "/etc/syslog-ng.conf"]
