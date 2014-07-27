# Makefile for Beginning Linux Programming 3rd Edition
# Chapter 10

DEBUG=debug1 debug2 debug3 debug4 debug0
CINFO=cinfo assert
#MEMORY=efence checker
MEMORY=checker

CC=gcc
CFLAGS=-g
LDFLAGS=-g

ALL= $(DEBUG) $(CINFO) $(MEMORY)

all: $(ALL)

cinfo: cinfo.o
	gcc -o cinfo cinfo.o $(LDFLAGS)

cinfo.o: cinfo.c
	gcc -c $(CFLAGS) -DDEBUG cinfo.c

assert: assert.o
	gcc -o assert $(LDFLAGS) assert.o -lm

# efence: efence.o
# 	gcc -o efence $(LDFLAGS) efence.o -lefence

checker: checker.o
	gcc -o checker checker.o $(LDFLAGS)

clean:
	@rm -f $(ALL) *~ *.o

debug: debug1 debug2 debug3 debug4 debug0
