#Uncomment and edit the line below if necessary
CFLAGS=-I/usr/include
LDFLAGS=-lncurses

#all: curses_app

curses_app: curses_app.o
	gcc -o curses_app curses_app.o $(LDFLAGS)

curses_app.o: curses_app.c
	gcc -c curses_app.c $(CFLAGS)

clean:
	rm curses_app.o curses_app
