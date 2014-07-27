#Uncomment and edit the line below if necessary
CFLAGS=-I/usr/include
LDFLAGS=-lncurses

#all: ipmode moveadd pad screen1 color keypad multiw1 subscl

screen1: screen1.o
	gcc -o screen1 screen1.o $(LDFLAGS)

screen1.o: screen1.c
	gcc -c screen1.c $(CFLAGS)

moveadd: moveadd.o
	gcc -o moveadd moveadd.o $(LDFLAGS)

moveadd.o: moveadd.c
	gcc -c moveadd.c $(CFLAGS)

ipmode: ipmode.o
	gcc -o ipmode ipmode.o $(LDFLAGS)

ipmode.o: ipmode.c
	gcc -c ipmode.c $(CFLAGS)

multiw1: multiw1.o
	gcc -o multiw1 multiw1.o $(LDFLAGS)

multiw1.o: multiw1.c
	gcc -c multiw1.c $(CFLAGS)

subscl: subscl.o
	gcc -o subscl subscl.o $(LDFLAGS)

subscl.o: subscl.c
	gcc -c subscl.c $(CFLAGS)

keypad: keypad.o
	gcc -o keypad keypad.o $(LDFLAGS)

keypad.o: keypad.c
	gcc -c keypad.c $(CFLAGS)

color: color.o
	gcc -o color color.o $(LDFLAGS)

color.o: color.c
	gcc -c color.c $(CFLAGS)

pad: pad.o
	gcc -o pad pad.o $(LDFLAGS)

pad.o: pad.c
	gcc -c pad.c $(CFLAGS)

clean:
	rm screen1.o screen1 moveadd.o moveadd ipmode.o ipmode multiw1.o multiw1 subscl.o subscl keypad.o keypad color.o color pad.o pad
