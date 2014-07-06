all: hello program

hello: hello.o
	gcc -o hello hello.o

hello.o: hello.c
	gcc -c hello.c

clean:
	rm hello.o hello program program.o fred.o bill.o libxixi.a

program: program.o libxixi.a
	gcc -o program program.o -L. -lxixi

fred.o: fred.c
	gcc -c fred.c

bill.o: bill.c
	gcc -c bill.c

libxixi.a: fred.o bill.o
	ar crv libxixi.a bill.o fred.o

program.o: program.c lib.h
	gcc -c -I. program.c
