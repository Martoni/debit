AM_CPPFLAGS	= -I../../
AM_CFLAGS	= -O3

AUTOMAKE_OPTIONS=subdir-objects

bin_PROGRAMS		= bitisolation
bitisolation_SOURCES	= state_db.c pip_db.c bitisolation.c \
			../../altera/bitarray.c algo_basic.c \
			algos.h  bitisolation_db.h  bitisolation.h  pip_db.h

bitisolation_CFLAGS	= $(AM_CFLAGS) @GLIB_CFLAGS@
bitisolation_LDADD	= @GLIB_LIBS@

