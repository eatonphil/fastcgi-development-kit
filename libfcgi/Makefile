# Makefile.in generated automatically by automake 1.5 from Makefile.am.

# Copyright 1994, 1995, 1996, 1997, 1998, 1999, 2000, 2001
# Free Software Foundation, Inc.
# This Makefile.in is free software; the Free Software Foundation
# gives unlimited permission to copy and/or distribute it,
# with or without modifications, as long as this notice is preserved.

# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY, to the extent permitted by law; without
# even the implied warranty of MERCHANTABILITY or FITNESS FOR A
# PARTICULAR PURPOSE.



# $Id: Makefile.am,v 1.9 2001/12/22 03:16:20 robs Exp $

SHELL = /bin/sh

srcdir = .
top_srcdir = ..

prefix = /usr/local
exec_prefix = ${prefix}

bindir = ${exec_prefix}/bin
sbindir = ${exec_prefix}/sbin
libexecdir = ${exec_prefix}/libexec
datadir = ${prefix}/share
sysconfdir = ${prefix}/etc
sharedstatedir = ${prefix}/com
localstatedir = /var
libdir = ${exec_prefix}/lib
infodir = /usr/local/info/
mandir = /usr/local/man
includedir = ${prefix}/include
oldincludedir = /usr/include
pkgdatadir = $(datadir)/fcgi
pkglibdir = $(libdir)/fcgi
pkgincludedir = $(includedir)/fcgi
top_builddir = ..

ACLOCAL = ${SHELL} /usr/ports/www/fcgi/work/fcgi-2.4.0/missing --run aclocal
AUTOCONF = ${SHELL} /usr/ports/www/fcgi/work/fcgi-2.4.0/missing --run autoconf
AUTOMAKE = ${SHELL} /usr/ports/www/fcgi/work/fcgi-2.4.0/missing --run automake
AUTOHEADER = ${SHELL} /usr/ports/www/fcgi/work/fcgi-2.4.0/missing --run autoheader

INSTALL = /usr/bin/install -c
INSTALL_PROGRAM = install  -s -m 555
INSTALL_DATA = install  -m 0644
INSTALL_SCRIPT = install  -m 555
INSTALL_HEADER = $(INSTALL_DATA)
transform = s,x,x,
NORMAL_INSTALL = :
PRE_INSTALL = :
POST_INSTALL = :
NORMAL_UNINSTALL = :
PRE_UNINSTALL = :
POST_UNINSTALL = :
host_alias = 
host_triplet = amd64-portbld-freebsd10.3
AMTAR = ${SHELL} /usr/ports/www/fcgi/work/fcgi-2.4.0/missing --run tar
AS = @AS@
AWK = /usr/bin/awk
CC = cc
CPP = cpp
CXX = c++
DEPDIR = .deps
DLLTOOL = @DLLTOOL@
ECHO = echo
ECHO_CPP = echo-cpp
EXEEXT = 
INSTALL_STRIP_PROGRAM = ${SHELL} $(install_sh) -c -s
LIBFCGIXX = libfcgi++.la
LIBTOOL = $(SHELL) $(top_builddir)/libtool
LN_S = ln -s
OBJDUMP = @OBJDUMP@
OBJEXT = o
PACKAGE = fcgi
PTHREAD_CC = cc
PTHREAD_CFLAGS = -D_THREAD_SAFE -pthread
PTHREAD_LIBS = 
RANLIB = ranlib
STRIP = strip
SYSTEM = unix
THREADED = threaded
VERSION = 2.4.0
am__include = include
am__quote = 
install_sh = /usr/ports/www/fcgi/work/fcgi-2.4.0/install-sh

INCLUDEDIR = ../include
CPPFLAGS =  -I$(top_srcdir)/include

INCLUDE_FILES = $(INCLUDEDIR)/fastcgi.h     \
                $(INCLUDEDIR)/fcgiapp.h     \
                $(INCLUDEDIR)/fcgimisc.h    \
                $(INCLUDEDIR)/fcgi_stdio.h  \
                $(INCLUDEDIR)/fcgios.h


lib_LTLIBRARIES = libfcgi.la libfcgi++.la
EXTRA_LTLIBRARIES = libfcgi++.la

libfcgi_la_SOURCES = $(INCLUDE_FILES)  \
                     fcgiapp.c         \
                     fcgi_stdio.c      \
                     os_unix.c

libfcgi_la_CC = cc
libfcgi_la_CFLAGS = -D_THREAD_SAFE -pthread

libfcgi___la_SOURCES = $(INCLUDE_FILES)       \
                       $(INCLUDEDIR)/fcgio.h  \
                       fcgio.cpp

libfcgi___la_CFLAGS = -D_THREAD_SAFE -pthread
libfcgi___la_LDFLAGS = -lfcgi -rpath ${exec_prefix}/lib
subdir = libfcgi
mkinstalldirs = $(SHELL) $(top_srcdir)/mkinstalldirs
CONFIG_HEADER = $(top_builddir)/fcgi_config.h
CONFIG_CLEAN_FILES =
LTLIBRARIES = $(lib_LTLIBRARIES)

libfcgi___la_LIBADD =
am_libfcgi___la_OBJECTS = fcgio.lo
libfcgi___la_OBJECTS = $(am_libfcgi___la_OBJECTS)
libfcgi_la_LDFLAGS =
libfcgi_la_LIBADD =
am_libfcgi_la_OBJECTS = libfcgi_la-fcgiapp.lo libfcgi_la-fcgi_stdio.lo \
	libfcgi_la-os_unix.lo
libfcgi_la_OBJECTS = $(am_libfcgi_la_OBJECTS)

DEFS = -DHAVE_CONFIG_H
DEFAULT_INCLUDES =  -I. -I$(srcdir) -I$(top_builddir)
LDFLAGS =  -fstack-protector
LIBS = 
depcomp = $(SHELL) $(top_srcdir)/depcomp
DEP_FILES = $(DEPDIR)/fcgio.Plo \
	$(DEPDIR)/libfcgi_la-fcgi_stdio.Plo \
	$(DEPDIR)/libfcgi_la-fcgiapp.Plo \
	$(DEPDIR)/libfcgi_la-os_unix.Plo
COMPILE = $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) \
	$(CPPFLAGS) $(AM_CFLAGS) $(CFLAGS)
LTCOMPILE = $(LIBTOOL) --mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) \
	$(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(AM_CFLAGS) $(CFLAGS)
CCLD = $(CC)
LINK = $(LIBTOOL) --mode=link $(CCLD) $(AM_CFLAGS) $(CFLAGS) \
	$(AM_LDFLAGS) $(LDFLAGS) -o $@
CFLAGS = -O2 -pipe  -fstack-protector -fno-strict-aliasing -Wall
CXXCOMPILE = $(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) \
	$(AM_CPPFLAGS) $(CPPFLAGS) $(AM_CXXFLAGS) $(CXXFLAGS)
LTCXXCOMPILE = $(LIBTOOL) --mode=compile $(CXX) $(DEFS) \
	$(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) \
	$(AM_CXXFLAGS) $(CXXFLAGS)
CXXLD = $(CXX)
CXXLINK = $(LIBTOOL) --mode=link $(CXXLD) $(AM_CXXFLAGS) $(CXXFLAGS) \
	$(AM_LDFLAGS) $(LDFLAGS) -o $@
CXXFLAGS = -O2 -pipe -fstack-protector -fno-strict-aliasing 
DIST_SOURCES = $(libfcgi___la_SOURCES) $(libfcgi_la_SOURCES)
DIST_COMMON = Makefile.am Makefile.in
SOURCES = $(libfcgi___la_SOURCES) $(libfcgi_la_SOURCES)

all: all-am

.SUFFIXES:
.SUFFIXES: .c .cpp .lo .o .obj

mostlyclean-libtool:
	-rm -f *.lo

clean-libtool:
	-rm -rf .libs _libs

distclean-libtool:
	-rm -f libtool
$(srcdir)/Makefile.in:  Makefile.am  $(top_srcdir)/configure.in $(ACLOCAL_M4)
	cd $(top_srcdir) && \
	  $(AUTOMAKE) --foreign  libfcgi/Makefile
Makefile:  $(srcdir)/Makefile.in  $(top_builddir)/config.status
	cd $(top_builddir) && \
	  CONFIG_HEADERS= CONFIG_LINKS= \
	  CONFIG_FILES=$(subdir)/$@ $(SHELL) ./config.status
install-libLTLIBRARIES: $(lib_LTLIBRARIES)
	@$(NORMAL_INSTALL)
	$(mkinstalldirs) $(DESTDIR)$(libdir)
	@list='$(lib_LTLIBRARIES)'; for p in $$list; do \
	  if test -f $$p; then \
	    echo " $(LIBTOOL) --mode=install $(INSTALL) $(INSTALL_STRIP_FLAG) $$p $(DESTDIR)$(libdir)/$$p"; \
	    $(LIBTOOL) --mode=install $(INSTALL) $(INSTALL_STRIP_FLAG) $$p $(DESTDIR)$(libdir)/$$p; \
	  else :; fi; \
	done

uninstall-libLTLIBRARIES:
	@$(NORMAL_UNINSTALL)
	@list='$(lib_LTLIBRARIES)'; for p in $$list; do \
	  echo " $(LIBTOOL) --mode=uninstall rm -f $(DESTDIR)$(libdir)/$$p"; \
	  $(LIBTOOL) --mode=uninstall rm -f $(DESTDIR)$(libdir)/$$p; \
	done

clean-libLTLIBRARIES:
	-test -z "$(lib_LTLIBRARIES)" || rm -f $(lib_LTLIBRARIES)
libfcgi++.la: $(libfcgi___la_OBJECTS) $(libfcgi___la_DEPENDENCIES) 
	$(CXXLINK)  $(libfcgi___la_LDFLAGS) $(libfcgi___la_OBJECTS) $(libfcgi___la_LIBADD) $(LIBS)
libfcgi_la-fcgiapp.lo: fcgiapp.c
libfcgi_la-fcgi_stdio.lo: fcgi_stdio.c
libfcgi_la-os_unix.lo: os_unix.c
libfcgi.la: $(libfcgi_la_OBJECTS) $(libfcgi_la_DEPENDENCIES) 
	$(LINK) -rpath $(libdir) $(libfcgi_la_LDFLAGS) $(libfcgi_la_OBJECTS) $(libfcgi_la_LIBADD) $(LIBS)

mostlyclean-compile:
	-rm -f *.$(OBJEXT) core *.core

distclean-compile:
	-rm -f *.tab.c

include $(DEPDIR)/fcgio.Plo
include $(DEPDIR)/libfcgi_la-fcgi_stdio.Plo
include $(DEPDIR)/libfcgi_la-fcgiapp.Plo
include $(DEPDIR)/libfcgi_la-os_unix.Plo

distclean-depend:
	-rm -rf $(DEPDIR)

.c.o:
	source='$<' object='$@' libtool=no \
	depfile='$(DEPDIR)/$*.Po' tmpdepfile='$(DEPDIR)/$*.TPo' \
	$(CCDEPMODE) $(depcomp) \
	$(COMPILE) -c `test -f $< || echo '$(srcdir)/'`$<

.c.obj:
	source='$<' object='$@' libtool=no \
	depfile='$(DEPDIR)/$*.Po' tmpdepfile='$(DEPDIR)/$*.TPo' \
	$(CCDEPMODE) $(depcomp) \
	$(COMPILE) -c `cygpath -w $<`

.c.lo:
	source='$<' object='$@' libtool=yes \
	depfile='$(DEPDIR)/$*.Plo' tmpdepfile='$(DEPDIR)/$*.TPlo' \
	$(CCDEPMODE) $(depcomp) \
	$(LTCOMPILE) -c -o $@ `test -f $< || echo '$(srcdir)/'`$<

libfcgi_la-fcgiapp.o: fcgiapp.c
	source='fcgiapp.c' object='libfcgi_la-fcgiapp.o' libtool=no \
	depfile='$(DEPDIR)/libfcgi_la-fcgiapp.Po' tmpdepfile='$(DEPDIR)/libfcgi_la-fcgiapp.TPo' \
	$(CCDEPMODE) $(depcomp) \
	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libfcgi_la_CFLAGS) $(CFLAGS) -c -o libfcgi_la-fcgiapp.o `test -f fcgiapp.c || echo '$(srcdir)/'`fcgiapp.c

libfcgi_la-fcgiapp.obj: fcgiapp.c
	source='fcgiapp.c' object='libfcgi_la-fcgiapp.obj' libtool=no \
	depfile='$(DEPDIR)/libfcgi_la-fcgiapp.Po' tmpdepfile='$(DEPDIR)/libfcgi_la-fcgiapp.TPo' \
	$(CCDEPMODE) $(depcomp) \
	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libfcgi_la_CFLAGS) $(CFLAGS) -c -o libfcgi_la-fcgiapp.obj `cygpath -w fcgiapp.c`

libfcgi_la-fcgiapp.lo: fcgiapp.c
	source='fcgiapp.c' object='libfcgi_la-fcgiapp.lo' libtool=yes \
	depfile='$(DEPDIR)/libfcgi_la-fcgiapp.Plo' tmpdepfile='$(DEPDIR)/libfcgi_la-fcgiapp.TPlo' \
	$(CCDEPMODE) $(depcomp) \
	$(LIBTOOL) --mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libfcgi_la_CFLAGS) $(CFLAGS) -c -o libfcgi_la-fcgiapp.lo `test -f fcgiapp.c || echo '$(srcdir)/'`fcgiapp.c

libfcgi_la-fcgi_stdio.o: fcgi_stdio.c
	source='fcgi_stdio.c' object='libfcgi_la-fcgi_stdio.o' libtool=no \
	depfile='$(DEPDIR)/libfcgi_la-fcgi_stdio.Po' tmpdepfile='$(DEPDIR)/libfcgi_la-fcgi_stdio.TPo' \
	$(CCDEPMODE) $(depcomp) \
	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libfcgi_la_CFLAGS) $(CFLAGS) -c -o libfcgi_la-fcgi_stdio.o `test -f fcgi_stdio.c || echo '$(srcdir)/'`fcgi_stdio.c

libfcgi_la-fcgi_stdio.obj: fcgi_stdio.c
	source='fcgi_stdio.c' object='libfcgi_la-fcgi_stdio.obj' libtool=no \
	depfile='$(DEPDIR)/libfcgi_la-fcgi_stdio.Po' tmpdepfile='$(DEPDIR)/libfcgi_la-fcgi_stdio.TPo' \
	$(CCDEPMODE) $(depcomp) \
	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libfcgi_la_CFLAGS) $(CFLAGS) -c -o libfcgi_la-fcgi_stdio.obj `cygpath -w fcgi_stdio.c`

libfcgi_la-fcgi_stdio.lo: fcgi_stdio.c
	source='fcgi_stdio.c' object='libfcgi_la-fcgi_stdio.lo' libtool=yes \
	depfile='$(DEPDIR)/libfcgi_la-fcgi_stdio.Plo' tmpdepfile='$(DEPDIR)/libfcgi_la-fcgi_stdio.TPlo' \
	$(CCDEPMODE) $(depcomp) \
	$(LIBTOOL) --mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libfcgi_la_CFLAGS) $(CFLAGS) -c -o libfcgi_la-fcgi_stdio.lo `test -f fcgi_stdio.c || echo '$(srcdir)/'`fcgi_stdio.c

libfcgi_la-os_unix.o: os_unix.c
	source='os_unix.c' object='libfcgi_la-os_unix.o' libtool=no \
	depfile='$(DEPDIR)/libfcgi_la-os_unix.Po' tmpdepfile='$(DEPDIR)/libfcgi_la-os_unix.TPo' \
	$(CCDEPMODE) $(depcomp) \
	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libfcgi_la_CFLAGS) $(CFLAGS) -c -o libfcgi_la-os_unix.o `test -f os_unix.c || echo '$(srcdir)/'`os_unix.c

libfcgi_la-os_unix.obj: os_unix.c
	source='os_unix.c' object='libfcgi_la-os_unix.obj' libtool=no \
	depfile='$(DEPDIR)/libfcgi_la-os_unix.Po' tmpdepfile='$(DEPDIR)/libfcgi_la-os_unix.TPo' \
	$(CCDEPMODE) $(depcomp) \
	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libfcgi_la_CFLAGS) $(CFLAGS) -c -o libfcgi_la-os_unix.obj `cygpath -w os_unix.c`

libfcgi_la-os_unix.lo: os_unix.c
	source='os_unix.c' object='libfcgi_la-os_unix.lo' libtool=yes \
	depfile='$(DEPDIR)/libfcgi_la-os_unix.Plo' tmpdepfile='$(DEPDIR)/libfcgi_la-os_unix.TPlo' \
	$(CCDEPMODE) $(depcomp) \
	$(LIBTOOL) --mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libfcgi_la_CFLAGS) $(CFLAGS) -c -o libfcgi_la-os_unix.lo `test -f os_unix.c || echo '$(srcdir)/'`os_unix.c
CCDEPMODE = depmode=gcc3

.cpp.o:
	source='$<' object='$@' libtool=no \
	depfile='$(DEPDIR)/$*.Po' tmpdepfile='$(DEPDIR)/$*.TPo' \
	$(CXXDEPMODE) $(depcomp) \
	$(CXXCOMPILE) -c -o $@ `test -f $< || echo '$(srcdir)/'`$<

.cpp.obj:
	source='$<' object='$@' libtool=no \
	depfile='$(DEPDIR)/$*.Po' tmpdepfile='$(DEPDIR)/$*.TPo' \
	$(CXXDEPMODE) $(depcomp) \
	$(CXXCOMPILE) -c -o $@ `cygpath -w $<`

.cpp.lo:
	source='$<' object='$@' libtool=yes \
	depfile='$(DEPDIR)/$*.Plo' tmpdepfile='$(DEPDIR)/$*.TPlo' \
	$(CXXDEPMODE) $(depcomp) \
	$(LTCXXCOMPILE) -c -o $@ `test -f $< || echo '$(srcdir)/'`$<
CXXDEPMODE = depmode=gcc3
uninstall-info-am:

tags: TAGS

ID: $(HEADERS) $(SOURCES) $(LISP) $(TAGS_FILES)
	list='$(SOURCES) $(HEADERS) $(TAGS_FILES)'; \
	unique=`for i in $$list; do \
	    if test -f "$$i"; then echo $$i; else echo $(srcdir)/$$i; fi; \
	  done | \
	  $(AWK) '    { files[$$0] = 1; } \
	       END { for (i in files) print i; }'`; \
	mkid -fID $$unique $(LISP)

TAGS:  $(HEADERS) $(SOURCES)  $(TAGS_DEPENDENCIES) \
		$(TAGS_FILES) $(LISP)
	tags=; \
	here=`pwd`; \
	list='$(SOURCES) $(HEADERS) $(TAGS_FILES)'; \
	unique=`for i in $$list; do \
	    if test -f "$$i"; then echo $$i; else echo $(srcdir)/$$i; fi; \
	  done | \
	  $(AWK) '    { files[$$0] = 1; } \
	       END { for (i in files) print i; }'`; \
	test -z "$(ETAGS_ARGS)$$unique$(LISP)$$tags" \
	  || etags $(ETAGS_ARGS) $$tags  $$unique $(LISP)

GTAGS:
	here=`CDPATH=: && cd $(top_builddir) && pwd` \
	  && cd $(top_srcdir) \
	  && gtags -i $(GTAGS_ARGS) $$here

distclean-tags:
	-rm -f TAGS ID GTAGS GRTAGS GSYMS GPATH

DISTFILES = $(DIST_COMMON) $(DIST_SOURCES) $(TEXINFOS) $(EXTRA_DIST)

top_distdir = ..
distdir = $(top_distdir)/$(PACKAGE)-$(VERSION)

distdir: $(DISTFILES)
	@for file in $(DISTFILES); do \
	  if test -f $$file; then d=.; else d=$(srcdir); fi; \
	  dir=`echo "$$file" | sed -e 's,/[^/]*$$,,'`; \
	  if test "$$dir" != "$$file" && test "$$dir" != "."; then \
	    $(mkinstalldirs) "$(distdir)/$$dir"; \
	  fi; \
	  if test -d $$d/$$file; then \
	    cp -pR $$d/$$file $(distdir) \
	    || exit 1; \
	  else \
	    test -f $(distdir)/$$file \
	    || cp -p $$d/$$file $(distdir)/$$file \
	    || exit 1; \
	  fi; \
	done
check-am: all-am
check: check-am
all-am: Makefile $(LTLIBRARIES)

installdirs:
	$(mkinstalldirs) $(DESTDIR)$(libdir)

install: install-am
install-exec: install-exec-am
install-data: install-data-am
uninstall: uninstall-am

install-am: all-am
	@$(MAKE) $(AM_MAKEFLAGS) install-exec-am install-data-am

installcheck: installcheck-am
install-strip:
	$(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	  `test -z '$(STRIP)' || \
	    echo "INSTALL_PROGRAM_ENV=STRIPPROG='$(STRIP)'"` install
mostlyclean-generic:

clean-generic:

distclean-generic:
	-rm -f Makefile $(CONFIG_CLEAN_FILES) stamp-h stamp-h[0-9]*

maintainer-clean-generic:
	@echo "This command is intended for maintainers to use"
	@echo "it deletes files that may require special tools to rebuild."
clean: clean-am

clean-am: clean-generic clean-libLTLIBRARIES clean-libtool \
	mostlyclean-am

distclean: distclean-am

distclean-am: clean-am distclean-compile distclean-depend \
	distclean-generic distclean-libtool distclean-tags

dvi: dvi-am

dvi-am:

info: info-am

info-am:

install-data-am:

install-exec-am: install-libLTLIBRARIES

install-info: install-info-am

install-man:

installcheck-am:

maintainer-clean: maintainer-clean-am

maintainer-clean-am: distclean-am maintainer-clean-generic

mostlyclean: mostlyclean-am

mostlyclean-am: mostlyclean-compile mostlyclean-generic \
	mostlyclean-libtool

uninstall-am: uninstall-info-am uninstall-libLTLIBRARIES

.PHONY: GTAGS all all-am check check-am clean clean-generic \
	clean-libLTLIBRARIES clean-libtool distclean distclean-compile \
	distclean-depend distclean-generic distclean-libtool \
	distclean-tags distdir dvi dvi-am info info-am install \
	install-am install-data install-data-am install-exec \
	install-exec-am install-info install-info-am \
	install-libLTLIBRARIES install-man install-strip installcheck \
	installcheck-am installdirs maintainer-clean \
	maintainer-clean-generic mostlyclean mostlyclean-compile \
	mostlyclean-generic mostlyclean-libtool tags uninstall \
	uninstall-am uninstall-info-am uninstall-libLTLIBRARIES

# Tell versions [3.59,3.63) of GNU make to not export all variables.
# Otherwise a system limit (for SysV at least) may be exceeded.
.NOEXPORT:
