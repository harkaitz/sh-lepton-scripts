.POSIX:
.SUFFIXES:
.PHONY: all clean install check

PROJECT   =lepton-scripts
VERSION   =1.0.0
PREFIX    =/usr/local
BUILDDIR ?=.build
UNAME_S  ?=$(shell uname -s)
EXE      ?=$(shell uname -s | awk '/Windows/ || /MSYS/ || /CYG/ { print ".exe" }')

all:
clean:
install:
check:
## -- BLOCK:license --
install: install-license
install-license: README.md COPYING COPYRIGHT
	mkdir -p $(DESTDIR)$(PREFIX)/share/doc/$(PROJECT)
	cp README.md COPYING COPYRIGHT $(DESTDIR)$(PREFIX)/share/doc/$(PROJECT)
## -- BLOCK:license --
## -- BLOCK:sh --
install: install-sh
install-sh:
	mkdir -p $(DESTDIR)$(PREFIX)/bin
	cp bin/lepton-h $(DESTDIR)$(PREFIX)/bin
	cp bin/np--lepton $(DESTDIR)$(PREFIX)/bin
	cp bin/wds_lepton $(DESTDIR)$(PREFIX)/bin
## -- BLOCK:sh --
