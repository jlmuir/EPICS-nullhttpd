TOP=..
include $(TOP)/configure/CONFIG

LIBRARY_IOC += nullhttpd

USR_CFLAGS_WIN32 += -DWIN32 -DNULLHTTPD_EXPORTS -DNULLHTTPD_DYNAMIC

INC += nullhttpd.h
nullhttpd_SRCS += cgi.c
nullhttpd_SRCS += files.c
nullhttpd_SRCS += http.c
nullhttpd_SRCS += win32.c
nullhttpd_SRCS += config.c
nullhttpd_SRCS += format.c
nullhttpd_SRCS += server.c
nullhttpd_SRCS += main.c

nullhttpd_SYS_LIBS_WIN32 += user32

include $(TOP)/configure/RULES

