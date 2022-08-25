PREFIX = /usr
MANDIR = $(PREFIX)/share/man

all:
	@echo Run \'make install\' to install Neofetch.

install:
	@mkdir -p $(DESTDIR)$(PREFIX)/bin
	@mkdir -p $(DESTDIR)$(MANDIR)/man1
	@cp -p neofetch $(DESTDIR)$(PREFIX)/bin/neofetch
	@chmod 755 $(DESTDIR)$(PREFIX)/bin/neofetch

uninstall:
	@rm -rf $(DESTDIR)$(PREFIX)/bin/neofetch
