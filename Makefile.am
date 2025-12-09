bin_PROGRAMS = helloworld

helloworld_SOURCES = hello_world.c hello_func.c

include_HEADERS = hello_make.h

MAINTAINERCLEANFILES = \
    Makefile.in \
    aclocal.m4 \
    configure \
    config.h.in \
    compile \
    depcomp \
    install-sh \
    missing

.PHONY: clean-all
clean-all: uninstall maintainer-clean
	@echo "Cleaned everything. Only *.c, *.h, *.am, *.ac, README.md remain."

