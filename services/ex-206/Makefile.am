
pkglib_LTLIBRARIES=srv_ex206.la

AM_CPPFLAGS=-I$(top_srcdir)/ -I$(top_srcdir)/include/ -I$(top_builddir)/include/

if IS_WIN32
EXT_MODULES_LIBADD=$(top_builddir)/libicapapi.la
endif

srv_ex206_la_LIBADD = $(EXT_MODULES_LIBADD) @MODULES_LIBADD@
srv_ex206_la_CFLAGS=  @MODULES_CFLAGS@
srv_ex206_la_LDFLAGS= -module -avoid-version
srv_ex206_la_SOURCES = srv_ex206.c

