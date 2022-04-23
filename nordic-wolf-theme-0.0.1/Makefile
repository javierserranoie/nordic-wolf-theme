PREFIX := /usr/share
DESTDIR ?=

.PHONY: setup
setup:
	mkdir -p $(DESTDIR)$(PREFIX)/themes/
	mkdir -p $(DESTDIR)$(PREFIX)/icons/
	mkdir -p $(DESTDIR)$(PREFIX)/backgrounds/

.PHONY: install
install:
	mv Nordic-darker-v40 ${DESTDIR}$(PREFIX)/themes/
	mv Nordic-v40 ${DESTDIR}$(PREFIX)/themes/
	mv Icons ${DESTDIR}$(PREFIX)/themes/
	mv install ${DESTDIR}$(PREFIX)/themes/
	mv papirus-folders ${DESTDIR}$(PREFIX)/themes/
	mv papirus-folders1 ${DESTDIR}$(PREFIX)/themes/
	mv Papirus ${DESTDIR}$(PREFIX)/icons/
	mv Papirus-Dark ${DESTDIR}$(PREFIX)/icons/
	mv Papirus-Light ${DESTDIR}$(PREFIX)/icons/
	mv BreezeX-Light ${DESTDIR}$(PREFIX)/icons/
	install -Dm644 wolf.png $(DESTDIR)$(PREFIX)/backgrounds/
