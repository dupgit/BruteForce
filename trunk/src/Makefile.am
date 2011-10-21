SUBDIRS =

DEFS = -I$(SRCDIR)  -I$(SRCDIR)/include	 		\
	   -DDATA_DIR=\"$(data_dir)\"				\
	   -DLOCALEDIR=\"$(LOCALEDIR)\"				\
	    $(CFLAGS) $(GLIB2_CFLAGS)

bin_PROGRAMS = heraia
heraia_LDFLAGS = $(LDFLAGS)
heraia_LDADD = $(GLIB2_LIBS)

heraia_SOURCES = 					\
	bruteforce.c    				\
	include/bruteforce.h

AM_CPPFLAGS = 			\
	$(GLIB2_CFLAGS)
