# Makefile.in generated by automake 1.11.1 from Makefile.am.
# Makefile.  Generated from Makefile.in by configure.

# Copyright (C) 1994, 1995, 1996, 1997, 1998, 1999, 2000, 2001, 2002,
# 2003, 2004, 2005, 2006, 2007, 2008, 2009  Free Software Foundation,
# Inc.
# This Makefile.in is free software; the Free Software Foundation
# gives unlimited permission to copy and/or distribute it,
# with or without modifications, as long as this notice is preserved.

# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY, to the extent permitted by law; without
# even the implied warranty of MERCHANTABILITY or FITNESS FOR A
# PARTICULAR PURPOSE.






pkgdatadir = $(datadir)/libnrx
pkgincludedir = $(includedir)/libnrx
pkglibdir = $(libdir)/libnrx
pkglibexecdir = $(libexecdir)/libnrx
am__cd = CDPATH="$${ZSH_VERSION+.}$(PATH_SEPARATOR)" && cd
install_sh_DATA = $(install_sh) -c -m 644
install_sh_PROGRAM = $(install_sh) -c
install_sh_SCRIPT = $(install_sh) -c
INSTALL_HEADER = $(INSTALL_DATA)
transform = $(program_transform_name)
NORMAL_INSTALL = :
PRE_INSTALL = :
POST_INSTALL = :
NORMAL_UNINSTALL = :
PRE_UNINSTALL = :
POST_UNINSTALL = :
noinst_PROGRAMS = test$(EXEEXT) test_trig$(EXEEXT) mibtable$(EXEEXT) \
	show_scan$(EXEEXT) btcoex_ratio$(EXEEXT)
subdir = .
DIST_COMMON = README $(am__configure_deps) $(include_HEADERS) \
	$(srcdir)/Makefile.am $(srcdir)/Makefile.in \
	$(srcdir)/config.h.in $(top_srcdir)/configure install-sh \
	missing strlcpy.c
ACLOCAL_M4 = $(top_srcdir)/aclocal.m4
am__aclocal_m4_deps = $(top_srcdir)/configure.ac
am__configure_deps = $(am__aclocal_m4_deps) $(CONFIGURE_DEPENDENCIES) \
	$(ACLOCAL_M4)
am__CONFIG_DISTCLEAN_FILES = config.status config.cache config.log \
 configure.lineno config.status.lineno
mkinstalldirs = $(install_sh) -d
CONFIG_HEADER = config.h
CONFIG_CLEAN_FILES =
CONFIG_CLEAN_VPATH_FILES =
am__vpath_adj_setup = srcdirstrip=`echo "$(srcdir)" | sed 's|.|.|g'`;
am__vpath_adj = case $$p in \
    $(srcdir)/*) f=`echo "$$p" | sed "s|^$$srcdirstrip/||"`;; \
    *) f=$$p;; \
  esac;
am__strip_dir = f=`echo $$p | sed -e 's|^.*/||'`;
am__install_max = 40
am__nobase_strip_setup = \
  srcdirstrip=`echo "$(srcdir)" | sed 's/[].[^$$\\*|]/\\\\&/g'`
am__nobase_strip = \
  for p in $$list; do echo "$$p"; done | sed -e "s|$$srcdirstrip/||"
am__nobase_list = $(am__nobase_strip_setup); \
  for p in $$list; do echo "$$p $$p"; done | \
  sed "s| $$srcdirstrip/| |;"' / .*\//!s/ .*/ ./; s,\( .*\)/[^/]*$$,\1,' | \
  $(AWK) 'BEGIN { files["."] = "" } { files[$$2] = files[$$2] " " $$1; \
    if (++n[$$2] == $(am__install_max)) \
      { print $$2, files[$$2]; n[$$2] = 0; files[$$2] = "" } } \
    END { for (dir in files) print dir, files[dir] }'
am__base_list = \
  sed '$$!N;$$!N;$$!N;$$!N;$$!N;$$!N;$$!N;s/\n/ /g' | \
  sed '$$!N;$$!N;$$!N;$$!N;s/\n/ /g'
am__installdirs = "$(DESTDIR)$(libdir)" "$(DESTDIR)$(includedir)"
LIBRARIES = $(lib_LIBRARIES)
AR = ar
ARFLAGS = cru
libnrx_a_AR = $(AR) $(ARFLAGS)
libnrx_a_DEPENDENCIES = $(LIBOBJS)
am_libnrx_a_OBJECTS = counters.$(OBJEXT) cvt.$(OBJEXT) event.$(OBJEXT) \
	ibss.$(OBJEXT) ifname.$(OBJEXT) init.$(OBJEXT) mib.$(OBJEXT) \
	param.$(OBJEXT) powersave.$(OBJEXT) printbuf.$(OBJEXT) \
	priomap.$(OBJEXT) radio.$(OBJEXT) roam.$(OBJEXT) \
	scan.$(OBJEXT) wext.$(OBJEXT)
libnrx_a_OBJECTS = $(am_libnrx_a_OBJECTS)
PROGRAMS = $(noinst_PROGRAMS)
am_btcoex_ratio_OBJECTS = btcoex_ratio.$(OBJEXT)
btcoex_ratio_OBJECTS = $(am_btcoex_ratio_OBJECTS)
btcoex_ratio_LDADD = $(LDADD)
btcoex_ratio_DEPENDENCIES = libnrx.a
mibtable_SOURCES = mibtable.c
mibtable_OBJECTS = mibtable.$(OBJEXT)
mibtable_LDADD = $(LDADD)
mibtable_DEPENDENCIES = libnrx.a
am_show_scan_OBJECTS = show_scan.$(OBJEXT) scan_support.$(OBJEXT)
show_scan_OBJECTS = $(am_show_scan_OBJECTS)
show_scan_LDADD = $(LDADD)
show_scan_DEPENDENCIES = libnrx.a
test_SOURCES = test.c
test_OBJECTS = test.$(OBJEXT)
test_LDADD = $(LDADD)
test_DEPENDENCIES = libnrx.a
test_trig_SOURCES = test_trig.c
test_trig_OBJECTS = test_trig.$(OBJEXT)
test_trig_LDADD = $(LDADD)
test_trig_DEPENDENCIES = libnrx.a
DEFAULT_INCLUDES = -I.
depcomp =
am__depfiles_maybe =
COMPILE = $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) \
	$(CPPFLAGS) $(AM_CFLAGS) $(CFLAGS)
CCLD = $(CC)
LINK = $(CCLD) $(AM_CFLAGS) $(CFLAGS) $(AM_LDFLAGS) $(LDFLAGS) -o $@
SOURCES = $(libnrx_a_SOURCES) $(btcoex_ratio_SOURCES) mibtable.c \
	$(show_scan_SOURCES) test.c test_trig.c
DIST_SOURCES = $(libnrx_a_SOURCES) $(btcoex_ratio_SOURCES) mibtable.c \
	$(show_scan_SOURCES) test.c test_trig.c
RECURSIVE_TARGETS = all-recursive check-recursive dvi-recursive \
	html-recursive info-recursive install-data-recursive \
	install-dvi-recursive install-exec-recursive \
	install-html-recursive install-info-recursive \
	install-pdf-recursive install-ps-recursive install-recursive \
	installcheck-recursive installdirs-recursive pdf-recursive \
	ps-recursive uninstall-recursive
HEADERS = $(include_HEADERS)
RECURSIVE_CLEAN_TARGETS = mostlyclean-recursive clean-recursive	\
  distclean-recursive maintainer-clean-recursive
AM_RECURSIVE_TARGETS = $(RECURSIVE_TARGETS:-recursive=) \
	$(RECURSIVE_CLEAN_TARGETS:-recursive=) tags TAGS ctags CTAGS \
	distdir dist dist-all distcheck
ETAGS = etags
CTAGS = ctags
DISTFILES = $(DIST_COMMON) $(DIST_SOURCES) $(TEXINFOS) $(EXTRA_DIST)
distdir = $(PACKAGE)-$(VERSION)
top_distdir = $(distdir)
am__remove_distdir = \
  { test ! -d "$(distdir)" \
    || { find "$(distdir)" -type d ! -perm -200 -exec chmod u+w {} ';' \
         && rm -fr "$(distdir)"; }; }
am__relativize = \
  dir0=`pwd`; \
  sed_first='s,^\([^/]*\)/.*$$,\1,'; \
  sed_rest='s,^[^/]*/*,,'; \
  sed_last='s,^.*/\([^/]*\)$$,\1,'; \
  sed_butlast='s,/*[^/]*$$,,'; \
  while test -n "$$dir1"; do \
    first=`echo "$$dir1" | sed -e "$$sed_first"`; \
    if test "$$first" != "."; then \
      if test "$$first" = ".."; then \
        dir2=`echo "$$dir0" | sed -e "$$sed_last"`/"$$dir2"; \
        dir0=`echo "$$dir0" | sed -e "$$sed_butlast"`; \
      else \
        first2=`echo "$$dir2" | sed -e "$$sed_first"`; \
        if test "$$first2" = "$$first"; then \
          dir2=`echo "$$dir2" | sed -e "$$sed_rest"`; \
        else \
          dir2="../$$dir2"; \
        fi; \
        dir0="$$dir0"/"$$first"; \
      fi; \
    fi; \
    dir1=`echo "$$dir1" | sed -e "$$sed_rest"`; \
  done; \
  reldir="$$dir2"
DIST_ARCHIVES = $(distdir).tar.gz
GZIP_ENV = --best
distuninstallcheck_listfiles = find . -type f -print
distcleancheck_listfiles = find . -type f -print
ACLOCAL = ${SHELL} /disk-b/6410/Android/wifi/nano-c047.12/userspace/libnrx/missing --run aclocal-1.11
AMTAR = ${SHELL} /disk-b/6410/Android/wifi/nano-c047.12/userspace/libnrx/missing --run tar
AUTOCONF = ${SHELL} /disk-b/6410/Android/wifi/nano-c047.12/userspace/libnrx/missing --run autoconf
AUTOHEADER = ${SHELL} /disk-b/6410/Android/wifi/nano-c047.12/userspace/libnrx/missing --run autoheader
AUTOMAKE = ${SHELL} /disk-b/6410/Android/wifi/nano-c047.12/userspace/libnrx/missing --run automake-1.11
AWK = mawk
CC = /disk-b/tools/amlogic/arm-2010q1/bin/arm-none-linux-gnueabi-gcc
CFLAGS = -I/disk-b/Amlogic/amlogicMBOX-0526/kernel/include -I/disk-b/6410/Android/wifi/nano-c047.12/kernel/ic -I/disk-b/6410/Android/wifi/nano-c047.12/driverenv/inc -I/disk-b/6410/Android/wifi/nano-c047.12/WiFiEngine/802/inc -I/disk-b/6410/Android/wifi/nano-c047.12/WiFiEngine/80211/inc -I/disk-b/6410/Android/wifi/nano-c047.12/WiFiEngine/80211macmgmt/inc -I/disk-b/6410/Android/wifi/nano-c047.12/WiFiEngine/80211macmib/inc -I/disk-b/6410/Android/wifi/nano-c047.12/WiFiEngine/driverenv/common/inc -I/disk-b/6410/Android/wifi/nano-c047.12/WiFiEngine/mac_api/inc -I/disk-b/6410/Android/wifi/nano-c047.12/WiFiEngine/pal/inc -I/disk-b/6410/Android/wifi/nano-c047.12/WiFiEngine/hic/inc -I/disk-b/6410/Android/wifi/nano-c047.12/WiFiEngine/hic_wrapper/inc -I/disk-b/6410/Android/wifi/nano-c047.12/WiFiEngine/hic_ctrl_msg/inc -I/disk-b/6410/Android/wifi/nano-c047.12/WiFiEngine/mac_wrapper/inc -I/disk-b/6410/Android/wifi/nano-c047.12/WiFiEngine/mlme_proxy/inc -I/disk-b/6410/Android/wifi/nano-c047.12/WiFiEngine/reg/inc -I/disk-b/6410/Android/wifi/nano-c047.12/WiFiEngine/sys/inc -I/disk-b/6410/Android/wifi/nano-c047.12/WiFiEngine/ucos/inc -I/disk-b/6410/Android/wifi/nano-c047.12/WiFiEngine/ucos_port_winhost/inc -I/disk-b/6410/Android/wifi/nano-c047.12/WiFiEngine/wifi_drv/inc -I/disk-b/6410/Android/wifi/nano-c047.12/WiFiEngine/ewpa/inc -I/disk-b/6410/Android/wifi/nano-c047.12/WiFiEngine/logger/inc
CPPFLAGS = 
CYGPATH_W = echo
DEFS = -DHAVE_CONFIG_H
ECHO_C = 
ECHO_N = -n
ECHO_T = 
EXEEXT = 
INSTALL = /usr/bin/install -c
INSTALL_DATA = ${INSTALL} -m 644
INSTALL_PROGRAM = ${INSTALL}
INSTALL_SCRIPT = ${INSTALL}
INSTALL_STRIP_PROGRAM = $(install_sh) -c -s
LDFLAGS = 
LIBOBJS =  ${LIBOBJDIR}strlcpy$U.o
LIBS = 
LTLIBOBJS =  ${LIBOBJDIR}strlcpy$U.lo
MAKEINFO = ${SHELL} /disk-b/6410/Android/wifi/nano-c047.12/userspace/libnrx/missing --run makeinfo
MKDIR_P = /bin/mkdir -p
OBJEXT = o
PACKAGE = libnrx
PACKAGE_BUGREPORT = support@nanoradio.com
PACKAGE_NAME = libnrx
PACKAGE_STRING = libnrx 0.0
PACKAGE_TARNAME = libnrx
PACKAGE_URL = 
PACKAGE_VERSION = 0.0
PATH_SEPARATOR = :
RANLIB = arm-none-linux-gnueabi-ranlib
SET_MAKE = 
SHELL = /bin/bash
STRIP = /disk-b/tools/amlogic/arm-2010q1/bin/arm-none-linux-gnueabi-strip
VERSION = 0.0
abs_builddir = /disk-b/6410/Android/wifi/nano-c047.12/userspace/libnrx
abs_srcdir = /disk-b/6410/Android/wifi/nano-c047.12/userspace/libnrx
abs_top_builddir = /disk-b/6410/Android/wifi/nano-c047.12/userspace/libnrx
abs_top_srcdir = /disk-b/6410/Android/wifi/nano-c047.12/userspace/libnrx
ac_ct_CC = 
am__leading_dot = .
am__tar = ${AMTAR} chof - "$$tardir"
am__untar = ${AMTAR} xf -
bindir = ${exec_prefix}/bin
build_alias = 
builddir = .
datadir = ${datarootdir}
datarootdir = ${prefix}/share
docdir = ${datarootdir}/doc/${PACKAGE_TARNAME}
dvidir = ${docdir}
exec_prefix = ${prefix}
host_alias = arm-none-linux-gnueabi
htmldir = ${docdir}
includedir = ${prefix}/include
infodir = ${datarootdir}/info
install_sh = ${SHELL} /disk-b/6410/Android/wifi/nano-c047.12/userspace/libnrx/install-sh
libdir = ${exec_prefix}/lib
libexecdir = ${exec_prefix}/libexec
localedir = ${datarootdir}/locale
localstatedir = ${prefix}/var
mandir = ${datarootdir}/man
mkdir_p = /bin/mkdir -p
oldincludedir = /usr/include
pdfdir = ${docdir}
prefix = /usr/local
program_transform_name = s,x,x,
psdir = ${docdir}
sbindir = ${exec_prefix}/sbin
sharedstatedir = ${prefix}/com
srcdir = .
sysconfdir = ${prefix}/etc
target_alias = 
top_build_prefix = 
top_builddir = .
top_srcdir = .
lib_LIBRARIES = libnrx.a
AM_CFLAGS = -Wall -Werror
SUBDIRS = . autotest
DIST_SUBDIRS = autotest
libnrx_a_SOURCES = \
	counters.c				\
	cvt.c					\
	event.c					\
	ibss.c					\
	ifname.c				\
	init.c					\
	mac_mib_defs.h				\
	mib.c					\
	nanoioctl.h				\
	nrx_lib.h				\
	nrx_priv.h				\
	nrx_proto.h				\
	param.c					\
	powersave.c				\
	printbuf.c				\
	priomap.c				\
	radio.c					\
	roam.c					\
	scan.c					\
	wext.c

libnrx_a_LIBADD = $(LIBOBJS)
include_HEADERS = nrx_lib.h nrx_proto.h
test_abar_CFLAGS = -pthread
show_scan_SOURCES = show_scan.c scan_support.c
btcoex_ratio_SOURCES = btcoex_ratio.c
LDADD = libnrx.a
HOSTDRIVER = $(top_srcdir)/../..
DISTCLEANFILES = nanoioctl.h mac_mib_defs.h
all: config.h
	$(MAKE) $(AM_MAKEFLAGS) all-recursive

.SUFFIXES:
.SUFFIXES: .c .o .obj
am--refresh:
	@:
$(srcdir)/Makefile.in:  $(srcdir)/Makefile.am  $(am__configure_deps)
	@for dep in $?; do \
	  case '$(am__configure_deps)' in \
	    *$$dep*) \
	      echo ' cd $(srcdir) && $(AUTOMAKE) --foreign --ignore-deps'; \
	      $(am__cd) $(srcdir) && $(AUTOMAKE) --foreign --ignore-deps \
		&& exit 0; \
	      exit 1;; \
	  esac; \
	done; \
	echo ' cd $(top_srcdir) && $(AUTOMAKE) --foreign --ignore-deps Makefile'; \
	$(am__cd) $(top_srcdir) && \
	  $(AUTOMAKE) --foreign --ignore-deps Makefile
.PRECIOUS: Makefile
Makefile: $(srcdir)/Makefile.in $(top_builddir)/config.status
	@case '$?' in \
	  *config.status*) \
	    echo ' $(SHELL) ./config.status'; \
	    $(SHELL) ./config.status;; \
	  *) \
	    echo ' cd $(top_builddir) && $(SHELL) ./config.status $@ $(am__depfiles_maybe)'; \
	    cd $(top_builddir) && $(SHELL) ./config.status $@ $(am__depfiles_maybe);; \
	esac;

$(top_builddir)/config.status: $(top_srcdir)/configure $(CONFIG_STATUS_DEPENDENCIES)
	$(SHELL) ./config.status --recheck

$(top_srcdir)/configure:  $(am__configure_deps)
	$(am__cd) $(srcdir) && $(AUTOCONF)
$(ACLOCAL_M4):  $(am__aclocal_m4_deps)
	$(am__cd) $(srcdir) && $(ACLOCAL) $(ACLOCAL_AMFLAGS)
$(am__aclocal_m4_deps):

config.h: stamp-h1
	@if test ! -f $@; then \
	  rm -f stamp-h1; \
	  $(MAKE) $(AM_MAKEFLAGS) stamp-h1; \
	else :; fi

stamp-h1: $(srcdir)/config.h.in $(top_builddir)/config.status
	@rm -f stamp-h1
	cd $(top_builddir) && $(SHELL) ./config.status config.h
$(srcdir)/config.h.in:  $(am__configure_deps) 
	($(am__cd) $(top_srcdir) && $(AUTOHEADER))
	rm -f stamp-h1
	touch $@

distclean-hdr:
	-rm -f config.h stamp-h1
install-libLIBRARIES: $(lib_LIBRARIES)
	@$(NORMAL_INSTALL)
	test -z "$(libdir)" || $(MKDIR_P) "$(DESTDIR)$(libdir)"
	@list='$(lib_LIBRARIES)'; test -n "$(libdir)" || list=; \
	list2=; for p in $$list; do \
	  if test -f $$p; then \
	    list2="$$list2 $$p"; \
	  else :; fi; \
	done; \
	test -z "$$list2" || { \
	  echo " $(INSTALL_DATA) $$list2 '$(DESTDIR)$(libdir)'"; \
	  $(INSTALL_DATA) $$list2 "$(DESTDIR)$(libdir)" || exit $$?; }
	@$(POST_INSTALL)
	@list='$(lib_LIBRARIES)'; test -n "$(libdir)" || list=; \
	for p in $$list; do \
	  if test -f $$p; then \
	    $(am__strip_dir) \
	    echo " ( cd '$(DESTDIR)$(libdir)' && $(RANLIB) $$f )"; \
	    ( cd "$(DESTDIR)$(libdir)" && $(RANLIB) $$f ) || exit $$?; \
	  else :; fi; \
	done

uninstall-libLIBRARIES:
	@$(NORMAL_UNINSTALL)
	@list='$(lib_LIBRARIES)'; test -n "$(libdir)" || list=; \
	files=`for p in $$list; do echo $$p; done | sed -e 's|^.*/||'`; \
	test -n "$$files" || exit 0; \
	echo " ( cd '$(DESTDIR)$(libdir)' && rm -f "$$files" )"; \
	cd "$(DESTDIR)$(libdir)" && rm -f $$files

clean-libLIBRARIES:
	-test -z "$(lib_LIBRARIES)" || rm -f $(lib_LIBRARIES)
libnrx.a: $(libnrx_a_OBJECTS) $(libnrx_a_DEPENDENCIES) 
	-rm -f libnrx.a
	$(libnrx_a_AR) libnrx.a $(libnrx_a_OBJECTS) $(libnrx_a_LIBADD)
	$(RANLIB) libnrx.a

clean-noinstPROGRAMS:
	-test -z "$(noinst_PROGRAMS)" || rm -f $(noinst_PROGRAMS)
btcoex_ratio$(EXEEXT): $(btcoex_ratio_OBJECTS) $(btcoex_ratio_DEPENDENCIES) 
	@rm -f btcoex_ratio$(EXEEXT)
	$(LINK) $(btcoex_ratio_OBJECTS) $(btcoex_ratio_LDADD) $(LIBS)
mibtable$(EXEEXT): $(mibtable_OBJECTS) $(mibtable_DEPENDENCIES) 
	@rm -f mibtable$(EXEEXT)
	$(LINK) $(mibtable_OBJECTS) $(mibtable_LDADD) $(LIBS)
show_scan$(EXEEXT): $(show_scan_OBJECTS) $(show_scan_DEPENDENCIES) 
	@rm -f show_scan$(EXEEXT)
	$(LINK) $(show_scan_OBJECTS) $(show_scan_LDADD) $(LIBS)
test$(EXEEXT): $(test_OBJECTS) $(test_DEPENDENCIES) 
	@rm -f test$(EXEEXT)
	$(LINK) $(test_OBJECTS) $(test_LDADD) $(LIBS)
test_trig$(EXEEXT): $(test_trig_OBJECTS) $(test_trig_DEPENDENCIES) 
	@rm -f test_trig$(EXEEXT)
	$(LINK) $(test_trig_OBJECTS) $(test_trig_LDADD) $(LIBS)

mostlyclean-compile:
	-rm -f *.$(OBJEXT)

distclean-compile:
	-rm -f *.tab.c

.c.o:
	$(COMPILE) -c $<

.c.obj:
	$(COMPILE) -c `$(CYGPATH_W) '$<'`
install-includeHEADERS: $(include_HEADERS)
	@$(NORMAL_INSTALL)
	test -z "$(includedir)" || $(MKDIR_P) "$(DESTDIR)$(includedir)"
	@list='$(include_HEADERS)'; test -n "$(includedir)" || list=; \
	for p in $$list; do \
	  if test -f "$$p"; then d=; else d="$(srcdir)/"; fi; \
	  echo "$$d$$p"; \
	done | $(am__base_list) | \
	while read files; do \
	  echo " $(INSTALL_HEADER) $$files '$(DESTDIR)$(includedir)'"; \
	  $(INSTALL_HEADER) $$files "$(DESTDIR)$(includedir)" || exit $$?; \
	done

uninstall-includeHEADERS:
	@$(NORMAL_UNINSTALL)
	@list='$(include_HEADERS)'; test -n "$(includedir)" || list=; \
	files=`for p in $$list; do echo $$p; done | sed -e 's|^.*/||'`; \
	test -n "$$files" || exit 0; \
	echo " ( cd '$(DESTDIR)$(includedir)' && rm -f" $$files ")"; \
	cd "$(DESTDIR)$(includedir)" && rm -f $$files

# This directory's subdirectories are mostly independent; you can cd
# into them and run `make' without going through this Makefile.
# To change the values of `make' variables: instead of editing Makefiles,
# (1) if the variable is set in `config.status', edit `config.status'
#     (which will cause the Makefiles to be regenerated when you run `make');
# (2) otherwise, pass the desired values on the `make' command line.
$(RECURSIVE_TARGETS):
	@fail= failcom='exit 1'; \
	for f in x $$MAKEFLAGS; do \
	  case $$f in \
	    *=* | --[!k]*);; \
	    *k*) failcom='fail=yes';; \
	  esac; \
	done; \
	dot_seen=no; \
	target=`echo $@ | sed s/-recursive//`; \
	list='$(SUBDIRS)'; for subdir in $$list; do \
	  echo "Making $$target in $$subdir"; \
	  if test "$$subdir" = "."; then \
	    dot_seen=yes; \
	    local_target="$$target-am"; \
	  else \
	    local_target="$$target"; \
	  fi; \
	  ($(am__cd) $$subdir && $(MAKE) $(AM_MAKEFLAGS) $$local_target) \
	  || eval $$failcom; \
	done; \
	if test "$$dot_seen" = "no"; then \
	  $(MAKE) $(AM_MAKEFLAGS) "$$target-am" || exit 1; \
	fi; test -z "$$fail"

$(RECURSIVE_CLEAN_TARGETS):
	@fail= failcom='exit 1'; \
	for f in x $$MAKEFLAGS; do \
	  case $$f in \
	    *=* | --[!k]*);; \
	    *k*) failcom='fail=yes';; \
	  esac; \
	done; \
	dot_seen=no; \
	case "$@" in \
	  distclean-* | maintainer-clean-*) list='$(DIST_SUBDIRS)' ;; \
	  *) list='$(SUBDIRS)' ;; \
	esac; \
	rev=''; for subdir in $$list; do \
	  if test "$$subdir" = "."; then :; else \
	    rev="$$subdir $$rev"; \
	  fi; \
	done; \
	rev="$$rev ."; \
	target=`echo $@ | sed s/-recursive//`; \
	for subdir in $$rev; do \
	  echo "Making $$target in $$subdir"; \
	  if test "$$subdir" = "."; then \
	    local_target="$$target-am"; \
	  else \
	    local_target="$$target"; \
	  fi; \
	  ($(am__cd) $$subdir && $(MAKE) $(AM_MAKEFLAGS) $$local_target) \
	  || eval $$failcom; \
	done && test -z "$$fail"
tags-recursive:
	list='$(SUBDIRS)'; for subdir in $$list; do \
	  test "$$subdir" = . || ($(am__cd) $$subdir && $(MAKE) $(AM_MAKEFLAGS) tags); \
	done
ctags-recursive:
	list='$(SUBDIRS)'; for subdir in $$list; do \
	  test "$$subdir" = . || ($(am__cd) $$subdir && $(MAKE) $(AM_MAKEFLAGS) ctags); \
	done

ID: $(HEADERS) $(SOURCES) $(LISP) $(TAGS_FILES)
	list='$(SOURCES) $(HEADERS) $(LISP) $(TAGS_FILES)'; \
	unique=`for i in $$list; do \
	    if test -f "$$i"; then echo $$i; else echo $(srcdir)/$$i; fi; \
	  done | \
	  $(AWK) '{ files[$$0] = 1; nonempty = 1; } \
	      END { if (nonempty) { for (i in files) print i; }; }'`; \
	mkid -fID $$unique
tags: TAGS

TAGS: tags-recursive $(HEADERS) $(SOURCES) config.h.in $(TAGS_DEPENDENCIES) \
		$(TAGS_FILES) $(LISP)
	set x; \
	here=`pwd`; \
	if ($(ETAGS) --etags-include --version) >/dev/null 2>&1; then \
	  include_option=--etags-include; \
	  empty_fix=.; \
	else \
	  include_option=--include; \
	  empty_fix=; \
	fi; \
	list='$(SUBDIRS)'; for subdir in $$list; do \
	  if test "$$subdir" = .; then :; else \
	    test ! -f $$subdir/TAGS || \
	      set "$$@" "$$include_option=$$here/$$subdir/TAGS"; \
	  fi; \
	done; \
	list='$(SOURCES) $(HEADERS) config.h.in $(LISP) $(TAGS_FILES)'; \
	unique=`for i in $$list; do \
	    if test -f "$$i"; then echo $$i; else echo $(srcdir)/$$i; fi; \
	  done | \
	  $(AWK) '{ files[$$0] = 1; nonempty = 1; } \
	      END { if (nonempty) { for (i in files) print i; }; }'`; \
	shift; \
	if test -z "$(ETAGS_ARGS)$$*$$unique"; then :; else \
	  test -n "$$unique" || unique=$$empty_fix; \
	  if test $$# -gt 0; then \
	    $(ETAGS) $(ETAGSFLAGS) $(AM_ETAGSFLAGS) $(ETAGS_ARGS) \
	      "$$@" $$unique; \
	  else \
	    $(ETAGS) $(ETAGSFLAGS) $(AM_ETAGSFLAGS) $(ETAGS_ARGS) \
	      $$unique; \
	  fi; \
	fi
ctags: CTAGS
CTAGS: ctags-recursive $(HEADERS) $(SOURCES) config.h.in $(TAGS_DEPENDENCIES) \
		$(TAGS_FILES) $(LISP)
	list='$(SOURCES) $(HEADERS) config.h.in $(LISP) $(TAGS_FILES)'; \
	unique=`for i in $$list; do \
	    if test -f "$$i"; then echo $$i; else echo $(srcdir)/$$i; fi; \
	  done | \
	  $(AWK) '{ files[$$0] = 1; nonempty = 1; } \
	      END { if (nonempty) { for (i in files) print i; }; }'`; \
	test -z "$(CTAGS_ARGS)$$unique" \
	  || $(CTAGS) $(CTAGSFLAGS) $(AM_CTAGSFLAGS) $(CTAGS_ARGS) \
	     $$unique

GTAGS:
	here=`$(am__cd) $(top_builddir) && pwd` \
	  && $(am__cd) $(top_srcdir) \
	  && gtags -i $(GTAGS_ARGS) "$$here"

distclean-tags:
	-rm -f TAGS ID GTAGS GRTAGS GSYMS GPATH tags

distdir: $(DISTFILES)
	$(am__remove_distdir)
	test -d "$(distdir)" || mkdir "$(distdir)"
	@srcdirstrip=`echo "$(srcdir)" | sed 's/[].[^$$\\*]/\\\\&/g'`; \
	topsrcdirstrip=`echo "$(top_srcdir)" | sed 's/[].[^$$\\*]/\\\\&/g'`; \
	list='$(DISTFILES)'; \
	  dist_files=`for file in $$list; do echo $$file; done | \
	  sed -e "s|^$$srcdirstrip/||;t" \
	      -e "s|^$$topsrcdirstrip/|$(top_builddir)/|;t"`; \
	case $$dist_files in \
	  */*) $(MKDIR_P) `echo "$$dist_files" | \
			   sed '/\//!d;s|^|$(distdir)/|;s,/[^/]*$$,,' | \
			   sort -u` ;; \
	esac; \
	for file in $$dist_files; do \
	  if test -f $$file || test -d $$file; then d=.; else d=$(srcdir); fi; \
	  if test -d $$d/$$file; then \
	    dir=`echo "/$$file" | sed -e 's,/[^/]*$$,,'`; \
	    if test -d "$(distdir)/$$file"; then \
	      find "$(distdir)/$$file" -type d ! -perm -700 -exec chmod u+rwx {} \;; \
	    fi; \
	    if test -d $(srcdir)/$$file && test $$d != $(srcdir); then \
	      cp -fpR $(srcdir)/$$file "$(distdir)$$dir" || exit 1; \
	      find "$(distdir)/$$file" -type d ! -perm -700 -exec chmod u+rwx {} \;; \
	    fi; \
	    cp -fpR $$d/$$file "$(distdir)$$dir" || exit 1; \
	  else \
	    test -f "$(distdir)/$$file" \
	    || cp -p $$d/$$file "$(distdir)/$$file" \
	    || exit 1; \
	  fi; \
	done
	@list='$(DIST_SUBDIRS)'; for subdir in $$list; do \
	  if test "$$subdir" = .; then :; else \
	    test -d "$(distdir)/$$subdir" \
	    || $(MKDIR_P) "$(distdir)/$$subdir" \
	    || exit 1; \
	  fi; \
	done
	@list='$(DIST_SUBDIRS)'; for subdir in $$list; do \
	  if test "$$subdir" = .; then :; else \
	    dir1=$$subdir; dir2="$(distdir)/$$subdir"; \
	    $(am__relativize); \
	    new_distdir=$$reldir; \
	    dir1=$$subdir; dir2="$(top_distdir)"; \
	    $(am__relativize); \
	    new_top_distdir=$$reldir; \
	    echo " (cd $$subdir && $(MAKE) $(AM_MAKEFLAGS) top_distdir="$$new_top_distdir" distdir="$$new_distdir" \\"; \
	    echo "     am__remove_distdir=: am__skip_length_check=: am__skip_mode_fix=: distdir)"; \
	    ($(am__cd) $$subdir && \
	      $(MAKE) $(AM_MAKEFLAGS) \
	        top_distdir="$$new_top_distdir" \
	        distdir="$$new_distdir" \
		am__remove_distdir=: \
		am__skip_length_check=: \
		am__skip_mode_fix=: \
	        distdir) \
	      || exit 1; \
	  fi; \
	done
	-test -n "$(am__skip_mode_fix)" \
	|| find "$(distdir)" -type d ! -perm -755 \
		-exec chmod u+rwx,go+rx {} \; -o \
	  ! -type d ! -perm -444 -links 1 -exec chmod a+r {} \; -o \
	  ! -type d ! -perm -400 -exec chmod a+r {} \; -o \
	  ! -type d ! -perm -444 -exec $(install_sh) -c -m a+r {} {} \; \
	|| chmod -R a+r "$(distdir)"
dist-gzip: distdir
	tardir=$(distdir) && $(am__tar) | GZIP=$(GZIP_ENV) gzip -c >$(distdir).tar.gz
	$(am__remove_distdir)

dist-bzip2: distdir
	tardir=$(distdir) && $(am__tar) | bzip2 -9 -c >$(distdir).tar.bz2
	$(am__remove_distdir)

dist-lzma: distdir
	tardir=$(distdir) && $(am__tar) | lzma -9 -c >$(distdir).tar.lzma
	$(am__remove_distdir)

dist-xz: distdir
	tardir=$(distdir) && $(am__tar) | xz -c >$(distdir).tar.xz
	$(am__remove_distdir)

dist-tarZ: distdir
	tardir=$(distdir) && $(am__tar) | compress -c >$(distdir).tar.Z
	$(am__remove_distdir)

dist-shar: distdir
	shar $(distdir) | GZIP=$(GZIP_ENV) gzip -c >$(distdir).shar.gz
	$(am__remove_distdir)

dist-zip: distdir
	-rm -f $(distdir).zip
	zip -rq $(distdir).zip $(distdir)
	$(am__remove_distdir)

dist dist-all: distdir
	tardir=$(distdir) && $(am__tar) | GZIP=$(GZIP_ENV) gzip -c >$(distdir).tar.gz
	$(am__remove_distdir)

# This target untars the dist file and tries a VPATH configuration.  Then
# it guarantees that the distribution is self-contained by making another
# tarfile.
distcheck: dist
	case '$(DIST_ARCHIVES)' in \
	*.tar.gz*) \
	  GZIP=$(GZIP_ENV) gzip -dc $(distdir).tar.gz | $(am__untar) ;;\
	*.tar.bz2*) \
	  bzip2 -dc $(distdir).tar.bz2 | $(am__untar) ;;\
	*.tar.lzma*) \
	  lzma -dc $(distdir).tar.lzma | $(am__untar) ;;\
	*.tar.xz*) \
	  xz -dc $(distdir).tar.xz | $(am__untar) ;;\
	*.tar.Z*) \
	  uncompress -c $(distdir).tar.Z | $(am__untar) ;;\
	*.shar.gz*) \
	  GZIP=$(GZIP_ENV) gzip -dc $(distdir).shar.gz | unshar ;;\
	*.zip*) \
	  unzip $(distdir).zip ;;\
	esac
	chmod -R a-w $(distdir); chmod a+w $(distdir)
	mkdir $(distdir)/_build
	mkdir $(distdir)/_inst
	chmod a-w $(distdir)
	test -d $(distdir)/_build || exit 0; \
	dc_install_base=`$(am__cd) $(distdir)/_inst && pwd | sed -e 's,^[^:\\/]:[\\/],/,'` \
	  && dc_destdir="$${TMPDIR-/tmp}/am-dc-$$$$/" \
	  && am__cwd=`pwd` \
	  && $(am__cd) $(distdir)/_build \
	  && ../configure --srcdir=.. --prefix="$$dc_install_base" \
	    $(DISTCHECK_CONFIGURE_FLAGS) \
	  && $(MAKE) $(AM_MAKEFLAGS) \
	  && $(MAKE) $(AM_MAKEFLAGS) dvi \
	  && $(MAKE) $(AM_MAKEFLAGS) check \
	  && $(MAKE) $(AM_MAKEFLAGS) install \
	  && $(MAKE) $(AM_MAKEFLAGS) installcheck \
	  && $(MAKE) $(AM_MAKEFLAGS) uninstall \
	  && $(MAKE) $(AM_MAKEFLAGS) distuninstallcheck_dir="$$dc_install_base" \
	        distuninstallcheck \
	  && chmod -R a-w "$$dc_install_base" \
	  && ({ \
	       (cd ../.. && umask 077 && mkdir "$$dc_destdir") \
	       && $(MAKE) $(AM_MAKEFLAGS) DESTDIR="$$dc_destdir" install \
	       && $(MAKE) $(AM_MAKEFLAGS) DESTDIR="$$dc_destdir" uninstall \
	       && $(MAKE) $(AM_MAKEFLAGS) DESTDIR="$$dc_destdir" \
	            distuninstallcheck_dir="$$dc_destdir" distuninstallcheck; \
	      } || { rm -rf "$$dc_destdir"; exit 1; }) \
	  && rm -rf "$$dc_destdir" \
	  && $(MAKE) $(AM_MAKEFLAGS) dist \
	  && rm -rf $(DIST_ARCHIVES) \
	  && $(MAKE) $(AM_MAKEFLAGS) distcleancheck \
	  && cd "$$am__cwd" \
	  || exit 1
	$(am__remove_distdir)
	@(echo "$(distdir) archives ready for distribution: "; \
	  list='$(DIST_ARCHIVES)'; for i in $$list; do echo $$i; done) | \
	  sed -e 1h -e 1s/./=/g -e 1p -e 1x -e '$$p' -e '$$x'
distuninstallcheck:
	@$(am__cd) '$(distuninstallcheck_dir)' \
	&& test `$(distuninstallcheck_listfiles) | wc -l` -le 1 \
	   || { echo "ERROR: files left after uninstall:" ; \
	        if test -n "$(DESTDIR)"; then \
	          echo "  (check DESTDIR support)"; \
	        fi ; \
	        $(distuninstallcheck_listfiles) ; \
	        exit 1; } >&2
distcleancheck: distclean
	@if test '$(srcdir)' = . ; then \
	  echo "ERROR: distcleancheck can only run from a VPATH build" ; \
	  exit 1 ; \
	fi
	@test `$(distcleancheck_listfiles) | wc -l` -eq 0 \
	  || { echo "ERROR: files left in build directory after distclean:" ; \
	       $(distcleancheck_listfiles) ; \
	       exit 1; } >&2
check-am: all-am
check: check-recursive
all-am: Makefile $(LIBRARIES) $(PROGRAMS) $(HEADERS) config.h
installdirs: installdirs-recursive
installdirs-am:
	for dir in "$(DESTDIR)$(libdir)" "$(DESTDIR)$(includedir)"; do \
	  test -z "$$dir" || $(MKDIR_P) "$$dir"; \
	done
install: install-recursive
install-exec: install-exec-recursive
install-data: install-data-recursive
uninstall: uninstall-recursive

install-am: all-am
	@$(MAKE) $(AM_MAKEFLAGS) install-exec-am install-data-am

installcheck: installcheck-recursive
install-strip:
	$(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	  install_sh_PROGRAM="$(INSTALL_STRIP_PROGRAM)" INSTALL_STRIP_FLAG=-s \
	  `test -z '$(STRIP)' || \
	    echo "INSTALL_PROGRAM_ENV=STRIPPROG='$(STRIP)'"` install
mostlyclean-generic:

clean-generic:

distclean-generic:
	-test -z "$(CONFIG_CLEAN_FILES)" || rm -f $(CONFIG_CLEAN_FILES)
	-test . = "$(srcdir)" || test -z "$(CONFIG_CLEAN_VPATH_FILES)" || rm -f $(CONFIG_CLEAN_VPATH_FILES)
	-test -z "$(DISTCLEANFILES)" || rm -f $(DISTCLEANFILES)

maintainer-clean-generic:
	@echo "This command is intended for maintainers to use"
	@echo "it deletes files that may require special tools to rebuild."
clean: clean-recursive

clean-am: clean-generic clean-libLIBRARIES clean-noinstPROGRAMS \
	mostlyclean-am

distclean: distclean-recursive
	-rm -f $(am__CONFIG_DISTCLEAN_FILES)
	-rm -f Makefile
distclean-am: clean-am distclean-compile distclean-generic \
	distclean-hdr distclean-tags

dvi: dvi-recursive

dvi-am:

html: html-recursive

html-am:

info: info-recursive

info-am:

install-data-am: install-includeHEADERS

install-dvi: install-dvi-recursive

install-dvi-am:

install-exec-am: install-libLIBRARIES

install-html: install-html-recursive

install-html-am:

install-info: install-info-recursive

install-info-am:

install-man:

install-pdf: install-pdf-recursive

install-pdf-am:

install-ps: install-ps-recursive

install-ps-am:

installcheck-am:

maintainer-clean: maintainer-clean-recursive
	-rm -f $(am__CONFIG_DISTCLEAN_FILES)
	-rm -rf $(top_srcdir)/autom4te.cache
	-rm -f Makefile
maintainer-clean-am: distclean-am maintainer-clean-generic

mostlyclean: mostlyclean-recursive

mostlyclean-am: mostlyclean-compile mostlyclean-generic

pdf: pdf-recursive

pdf-am:

ps: ps-recursive

ps-am:

uninstall-am: uninstall-includeHEADERS uninstall-libLIBRARIES

.MAKE: $(RECURSIVE_CLEAN_TARGETS) $(RECURSIVE_TARGETS) all \
	ctags-recursive install-am install-strip tags-recursive

.PHONY: $(RECURSIVE_CLEAN_TARGETS) $(RECURSIVE_TARGETS) CTAGS GTAGS \
	all all-am am--refresh check check-am clean clean-generic \
	clean-libLIBRARIES clean-noinstPROGRAMS ctags ctags-recursive \
	dist dist-all dist-bzip2 dist-gzip dist-lzma dist-shar \
	dist-tarZ dist-xz dist-zip distcheck distclean \
	distclean-compile distclean-generic distclean-hdr \
	distclean-tags distcleancheck distdir distuninstallcheck dvi \
	dvi-am html html-am info info-am install install-am \
	install-data install-data-am install-dvi install-dvi-am \
	install-exec install-exec-am install-html install-html-am \
	install-includeHEADERS install-info install-info-am \
	install-libLIBRARIES install-man install-pdf install-pdf-am \
	install-ps install-ps-am install-strip installcheck \
	installcheck-am installdirs installdirs-am maintainer-clean \
	maintainer-clean-generic mostlyclean mostlyclean-compile \
	mostlyclean-generic pdf pdf-am ps ps-am tags tags-recursive \
	uninstall uninstall-am uninstall-includeHEADERS \
	uninstall-libLIBRARIES


$(libnrx_a_OBJECTS): $(srcdir)/nrx_proto.h $(srcdir)/nrx_priv.h
$(srcdir)/nrx_proto.h $(srcdir)/nrx_priv.h: $(filter %.c, $(libnrx_a_SOURCES))
	chmod +x autotest/replace_nanokey
	cd $(srcdir) && perl make-proto.pl -o nrx_proto.h -p nrx_priv.h $(filter %.c, $(libnrx_a_SOURCES))

$(libnrx_a_OBJECTS): nanoioctl.h mac_mib_defs.h

nanoioctl.h: $(HOSTDRIVER)/kernel/ic/nanoioctl.h
	cp -p $(HOSTDRIVER)/kernel/ic/nanoioctl.h nanoioctl.h

mac_mib_defs.h: $(HOSTDRIVER)/WiFiEngine/wifi_drv/inc/mib_defs.h
	cp -p $(HOSTDRIVER)/WiFiEngine/wifi_drv/inc/mib_defs.h mac_mib_defs.h

# Tell versions [3.59,3.63) of GNU make to not export all variables.
# Otherwise a system limit (for SysV at least) may be exceeded.
.NOEXPORT:
