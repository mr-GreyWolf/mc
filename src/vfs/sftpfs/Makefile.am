
AM_CPPFLAGS = $(GLIB_CFLAGS) -I$(top_srcdir) $(LIBSSH_CFLAGS) $(PCRE_CPPFLAGS)

noinst_LTLIBRARIES = libvfs-sftpfs.la

libvfs_sftpfs_la_SOURCES = \
	config_parser.c \
	connection.c \
	dir.c \
	file.c \
	init.c init.h \
	internal.c internal.h \
	vfs_class.c \
	vfs_subclass.c
