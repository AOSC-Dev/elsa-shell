noinst_LTLIBRARIES = libelsa-wm.la

libelsa_wm_la_SOURCES =	elsa-wm-plugin.c	\
						background.c	\
						switcher.c	\
						shell-app.c	\
						shell-window-tracker.c	\
						shell-app-system.c	\
						overview.c	\
						ov_header.c	\
						$(NULL)
libelsa_wm_la_CFLAGS = $(MUTTER_CFLAGS)	\
					   $(SN_CFLAGS)	\
					   $(XML2_CFLAGS)
libelsa_wm_la_LIBADD = $(MUTTER_LIBS)	\
					   $(SN_LIBS)	\
					   $(XML2_LIBS)
