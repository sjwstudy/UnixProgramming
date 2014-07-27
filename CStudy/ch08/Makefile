# Makefile for Beginning Linux Programming 3rd Edition
# Chapter 8

# CONNECT=connect1 connect2
# INSERT=insert1 insert2
# SELECT=select1 select2 select3 select4
# UPDATE=update1

# ALL=$(CONNECT) $(INSERT) $(SELECT) $(UPDATE)

# all: $(ALL)

CFLAGS=-I/usr/include/mysql
# LDFLAGS=-lmysqlclient
LDFLAGS=-lmysqlclient


clean:
	@rm -f connect1.o connect1 connect2.o connect2

connect1: connect1.o
	gcc -o connect1 connect1.o $(LDFLAGS)

connect1.o: connect1.c
	gcc -c connect1.c $(CFLAGS)

connect2: connect2.o
	gcc -o connect2 connect2.o $(LDFLAGS)

connect2.o: connect2.c
	gcc -c connect2.c $(CFLAGS)
