AM_CPPFLAGS = -I$(top_srcdir)/include
AM_CPPFLAGS += -DSERIAL_DEBUG

noinst_LIBRARIES = libserial.a

libserial_a_SOURCES =	directserial.cpp directserial.h \
						libserial.cpp libserial.h \
						serialdummy.cpp serialdummy.h serialport.cpp \
						softmodem.cpp softmodem.h misc_util.cpp misc_util.h \
						nullmodem.cpp nullmodem.h custbaud.h custbaud.cpp termbits2.h termios2.cpp termios2.h
