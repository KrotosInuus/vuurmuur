AM_CPPFLAGS = 
METASOURCES = AUTO
bin_PROGRAMS = vuurmuur_log
vuurmuur_log_SOURCES = logfile.c vuurmuur_log.c nflog.c stats.c vuurmuur_ipc.c

vuurmuur_log_LDADD = -lvuurmuur $(LIBNETFILTER_LOG_LIBS)
noinst_HEADERS = vuurmuur_log.h logfile.h stats.h nflog.h vuurmuur_ipc.h

