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



# $Id: Makefile.am,v 1.8 2001/12/22 03:16:21 robs Exp $

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
infodir = /usr/local/info
mandir = /usr/local/man
includedir = ${prefix}/include
oldincludedir = /usr/include
pkgdatadir = $(datadir)/fcgi
pkglibdir = $(libdir)/fcgi
pkgincludedir = $(includedir)/fcgi
top_builddir = ..

ACLOCAL = aclocal-1.15
AUTOCONF = autoconf
AUTOMAKE = automake-1.15
AUTOHEADER = autoheader

INSTALL = /usr/bin/install -c
INSTALL_PROGRAM = ${INSTALL}
INSTALL_DATA = ${INSTALL} -m 644
INSTALL_SCRIPT = ${INSTALL}
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
AMTAR = $${TAR-tar}
AS = @AS@
AWK = nawk
CC = cc
CPP = cpp
CXX = c++
DEPDIR = .deps
DLLTOOL = false
ECHO = @ECHO@
ECHO_CPP = echo-cpp
EXEEXT = 
INSTALL_STRIP_PROGRAM = $(install_sh) -c -s
LIBFCGIXX = libfcgi++.la
LIBTOOL = $(SHELL) $(top_builddir)/libtool
LN_S = ln -s
OBJDUMP = objdump
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
install_sh = ${SHELL} /home/phil/vendor/fastcgi-development-kit/install-sh

noinst_PROGRAMS = authorizer        \
                      echo              \
                      echo-x            \
                      log-dump          \
                      size              \
                      threaded        \
                      echo-cpp


EXTRA_PROGRAMS = threaded echo-cpp

INCLUDEDIR = ../include
CPPFLAGS =  -I$(top_srcdir)/include

INCLUDE_FILES = $(INCLUDEDIR)/fastcgi.h    \
                  $(INCLUDEDIR)/fcgiapp.h    \
                  $(INCLUDEDIR)/fcgimisc.h   \
                  $(INCLUDEDIR)/fcgi_stdio.h


LIBDIR = ../libfcgi
LIBFCGI = $(LIBDIR)/libfcgi.la

LDADD = $(LIBFCGI)

echo_SOURCES = $(INCLUDE_FILES) echo.c
echo_x_SOURCES = $(INCLUDE_FILES) echo-x.c
log_dump_SOURCES = $(INCLUDE_FILES) log-dump.c
authorizer_SOURCES = $(INCLUDE_FILES) authorizer.c

threaded_SOURCES = $(INCLUDE_FILES) threaded.c
threaded_CC = cc
threaded_CFLAGS = -D_THREAD_SAFE -pthread
threaded_LDFLAGS = -D_THREAD_SAFE -pthread 

echo_cpp_SOURCES = $(INCLUDE_FILES) $(INCLUDEDIR)/fcgio.h echo-cpp.cpp
echo_cpp_LDADD = $(LIBDIR)/libfcgi++.la $(LIBFCGI)
subdir = examples
mkinstalldirs = $(SHELL) $(top_srcdir)/mkinstalldirs
CONFIG_HEADER = $(top_builddir)/fcgi_config.h
CONFIG_CLEAN_FILES =
EXTRA_PROGRAMS = threaded$(EXEEXT) echo-cpp$(EXEEXT)
noinst_PROGRAMS = authorizer$(EXEEXT) echo$(EXEEXT) echo-x$(EXEEXT) \
	log-dump$(EXEEXT) size$(EXEEXT) threaded echo-cpp
PROGRAMS = $(noinst_PROGRAMS)

am_authorizer_OBJECTS = authorizer.$(OBJEXT)
authorizer_OBJECTS = $(am_authorizer_OBJECTS)
authorizer_LDADD = $(LDADD)
authorizer_DEPENDENCIES = $(LIBDIR)/libfcgi.la
authorizer_LDFLAGS =
am_echo_OBJECTS = echo.$(OBJEXT)
echo_OBJECTS = $(am_echo_OBJECTS)
echo_LDADD = $(LDADD)
echo_DEPENDENCIES = $(LIBDIR)/libfcgi.la
echo_LDFLAGS =
am_echo_cpp_OBJECTS = echo-cpp.$(OBJEXT)
echo_cpp_OBJECTS = $(am_echo_cpp_OBJECTS)
echo_cpp_DEPENDENCIES = $(LIBDIR)/libfcgi++.la
echo_cpp_LDFLAGS =
am_echo_x_OBJECTS = echo-x.$(OBJEXT)
echo_x_OBJECTS = $(am_echo_x_OBJECTS)
echo_x_LDADD = $(LDADD)
echo_x_DEPENDENCIES = $(LIBDIR)/libfcgi.la
echo_x_LDFLAGS =
am_log_dump_OBJECTS = log-dump.$(OBJEXT)
log_dump_OBJECTS = $(am_log_dump_OBJECTS)
log_dump_LDADD = $(LDADD)
log_dump_DEPENDENCIES = $(LIBDIR)/libfcgi.la
log_dump_LDFLAGS =
size_SOURCES = size.c
size_OBJECTS = size.$(OBJEXT)
size_LDADD = $(LDADD)
size_DEPENDENCIES = $(LIBDIR)/libfcgi.la
size_LDFLAGS =
am_threaded_OBJECTS = threaded-threaded.$(OBJEXT)
threaded_OBJECTS = $(am_threaded_OBJECTS)
threaded_LDADD = $(LDADD)
threaded_DEPENDENCIES = $(LIBDIR)/libfcgi.la

DEFS = -DHAVE_CONFIG_H
DEFAULT_INCLUDES =  -I. -I$(srcdir) -I$(top_builddir)
LDFLAGS =  -fstack-protector
LIBS = 
depcomp = $(SHELL) $(top_srcdir)/depcomp
DEP_FILES = $(DEPDIR)/authorizer.Po $(DEPDIR)/echo-cpp.Po \
	$(DEPDIR)/echo-x.Po $(DEPDIR)/echo.Po \
	$(DEPDIR)/log-dump.Po $(DEPDIR)/size.Po \
	$(DEPDIR)/threaded-threaded.Po
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
DIST_SOURCES = $(authorizer_SOURCES) $(echo_SOURCES) $(echo_cpp_SOURCES) \
	$(echo_x_SOURCES) $(log_dump_SOURCES) size.c \
	$(threaded_SOURCES)
DIST_COMMON = Makefile.am Makefile.in
SOURCES = $(authorizer_SOURCES) $(echo_SOURCES) $(echo_cpp_SOURCES) $(echo_x_SOURCES) $(log_dump_SOURCES) size.c $(threaded_SOURCES)

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
	  $(AUTOMAKE) --foreign  examples/Makefile
Makefile:  $(srcdir)/Makefile.in  $(top_builddir)/config.status
	cd $(top_builddir) && \
	  CONFIG_HEADERS= CONFIG_LINKS= \
	  CONFIG_FILES=$(subdir)/$@ $(SHELL) ./config.status

clean-noinstPROGRAMS:
	-test -z "$(noinst_PROGRAMS)" || rm -f $(noinst_PROGRAMS)
authorizer$(EXEEXT): $(authorizer_OBJECTS) $(authorizer_DEPENDENCIES) 
	@rm -f authorizer$(EXEEXT)
	$(LINK) $(authorizer_LDFLAGS) $(authorizer_OBJECTS) $(authorizer_LDADD) $(LIBS)
echo$(EXEEXT): $(echo_OBJECTS) $(echo_DEPENDENCIES) 
	@rm -f echo$(EXEEXT)
	$(LINK) $(echo_LDFLAGS) $(echo_OBJECTS) $(echo_LDADD) $(LIBS)
echo-cpp$(EXEEXT): $(echo_cpp_OBJECTS) $(echo_cpp_DEPENDENCIES) 
	@rm -f echo-cpp$(EXEEXT)
	$(CXXLINK) $(echo_cpp_LDFLAGS) $(echo_cpp_OBJECTS) $(echo_cpp_LDADD) $(LIBS)
echo-x$(EXEEXT): $(echo_x_OBJECTS) $(echo_x_DEPENDENCIES) 
	@rm -f echo-x$(EXEEXT)
	$(LINK) $(echo_x_LDFLAGS) $(echo_x_OBJECTS) $(echo_x_LDADD) $(LIBS)
log-dump$(EXEEXT): $(log_dump_OBJECTS) $(log_dump_DEPENDENCIES) 
	@rm -f log-dump$(EXEEXT)
	$(LINK) $(log_dump_LDFLAGS) $(log_dump_OBJECTS) $(log_dump_LDADD) $(LIBS)
size$(EXEEXT): $(size_OBJECTS) $(size_DEPENDENCIES) 
	@rm -f size$(EXEEXT)
	$(LINK) $(size_LDFLAGS) $(size_OBJECTS) $(size_LDADD) $(LIBS)
threaded-threaded.$(OBJEXT): threaded.c
threaded$(EXEEXT): $(threaded_OBJECTS) $(threaded_DEPENDENCIES) 
	@rm -f threaded$(EXEEXT)
	$(LINK) $(threaded_LDFLAGS) $(threaded_OBJECTS) $(threaded_LDADD) $(LIBS)

mostlyclean-compile:
	-rm -f *.$(OBJEXT) core *.core

distclean-compile:
	-rm -f *.tab.c

include $(DEPDIR)/authorizer.Po
include $(DEPDIR)/echo-cpp.Po
include $(DEPDIR)/echo-x.Po
include $(DEPDIR)/echo.Po
include $(DEPDIR)/log-dump.Po
include $(DEPDIR)/size.Po
include $(DEPDIR)/threaded-threaded.Po

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

threaded-threaded.o: threaded.c
	source='threaded.c' object='threaded-threaded.o' libtool=no \
	depfile='$(DEPDIR)/threaded-threaded.Po' tmpdepfile='$(DEPDIR)/threaded-threaded.TPo' \
	$(CCDEPMODE) $(depcomp) \
	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(threaded_CFLAGS) $(CFLAGS) -c -o threaded-threaded.o `test -f threaded.c || echo '$(srcdir)/'`threaded.c

threaded-threaded.obj: threaded.c
	source='threaded.c' object='threaded-threaded.obj' libtool=no \
	depfile='$(DEPDIR)/threaded-threaded.Po' tmpdepfile='$(DEPDIR)/threaded-threaded.TPo' \
	$(CCDEPMODE) $(depcomp) \
	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(threaded_CFLAGS) $(CFLAGS) -c -o threaded-threaded.obj `cygpath -w threaded.c`

threaded-threaded.lo: threaded.c
	source='threaded.c' object='threaded-threaded.lo' libtool=yes \
	depfile='$(DEPDIR)/threaded-threaded.Plo' tmpdepfile='$(DEPDIR)/threaded-threaded.TPlo' \
	$(CCDEPMODE) $(depcomp) \
	$(LIBTOOL) --mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(threaded_CFLAGS) $(CFLAGS) -c -o threaded-threaded.lo `test -f threaded.c || echo '$(srcdir)/'`threaded.c
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
all-am: Makefile $(PROGRAMS)

installdirs:

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

clean-am: clean-generic clean-libtool clean-noinstPROGRAMS \
	mostlyclean-am

distclean: distclean-am

distclean-am: clean-am distclean-compile distclean-depend \
	distclean-generic distclean-libtool distclean-tags

dvi: dvi-am

dvi-am:

info: info-am

info-am:

install-data-am:

install-exec-am:

install-info: install-info-am

install-man:

installcheck-am:

maintainer-clean: maintainer-clean-am

maintainer-clean-am: distclean-am maintainer-clean-generic

mostlyclean: mostlyclean-am

mostlyclean-am: mostlyclean-compile mostlyclean-generic \
	mostlyclean-libtool

uninstall-am: uninstall-info-am

.PHONY: GTAGS all all-am check check-am clean clean-generic \
	clean-libtool clean-noinstPROGRAMS distclean distclean-compile \
	distclean-depend distclean-generic distclean-libtool \
	distclean-tags distdir dvi dvi-am info info-am install \
	install-am install-data install-data-am install-exec \
	install-exec-am install-info install-info-am install-man \
	install-strip installcheck installcheck-am installdirs \
	maintainer-clean maintainer-clean-generic mostlyclean \
	mostlyclean-compile mostlyclean-generic mostlyclean-libtool \
	tags uninstall uninstall-am uninstall-info-am

# Tell versions [3.59,3.63) of GNU make to not export all variables.
# Otherwise a system limit (for SysV at least) may be exceeded.
.NOEXPORT:
