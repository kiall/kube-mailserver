SUBDIRS := base clamav dovecot postfix postfixadmin rspamd syslog-ng-sidecar

all: $(SUBDIRS)

$(SUBDIRS):
	$(MAKE) -C $@

.PHONY: all $(SUBDIRS)
