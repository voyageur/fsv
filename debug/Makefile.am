if DEBUG
DEBUG_LIBS = libdebug.a
else
DEBUG_LIBS =
endif

AM_CFLAGS = @GTK_CFLAGS@

noinst_LIBRARIES = $(DEBUG_LIBS)

noinst_HEADERS = debug.h
libdebug_a_SOURCES = debug.c
