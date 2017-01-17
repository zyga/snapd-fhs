EXTRA_DIST=LICENSE README.md

.PHONY: install-data-local
install-data-local:
	install -d -m 755 $(DESTDIR)/
	install -d -m 755 $(DESTDIR)/var/lib/snapd/snap/
	ln -s /var/lib/snapd/snap $(DESTDIR)/snap
