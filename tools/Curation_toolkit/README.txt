installation of cross_match

you need to have a gcc compiler and in Ubuntu 22.04, modify the makefile to this:
CC= gcc
CFLAGS= -O2 -fcommon
LFLAGS= -lm