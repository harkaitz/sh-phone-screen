PROJECT=phone-screen
VERSION=1.0.0
DESTDIR =
PREFIX  =/usr/local

all:
clean:
install:
update:

## -- BLOCK:license --
install: install-license
install-license: 
	mkdir -p $(DESTDIR)$(PREFIX)/share/doc/$(PROJECT)
	cp LICENSE README.md $(DESTDIR)$(PREFIX)/share/doc/$(PROJECT)
update: update-license
update-license:
	ssnip README.md
## -- BLOCK:license --
## -- BLOCK:sh --
install: install-sh
install-sh:
	mkdir -p $(DESTDIR)$(PREFIX)/bin
	cp bin/phone-screen     $(DESTDIR)$(PREFIX)/bin
install: install-share
install-share:
	mkdir -p $(DESTDIR)$(PREFIX)/share
	cp -r share/phone-screen $(DESTDIR)$(PREFIX)/share
## -- BLOCK:sh --
