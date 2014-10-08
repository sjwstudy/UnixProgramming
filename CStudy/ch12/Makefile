CC=gcc
CFLAGS=-D_REENTRANT
LDFLAGS=-lpthread

thread: thread1 thread2 thread3 thread3a thread4 thread5 thread6 thread6a thread7 thread8 thread8a

clean:
	rm -f thread1 thread2 thread3 thread3a thread4 thread5 thread6 thread6a thread7 thread7a thread8 thread8a

thread1: thread1.c
	gcc  ${CFLAGS} thread1.c -o thread1 ${LDFLAGS}

thread2: thread2.c
	gcc ${CFLAGS} thread2.c -o thread2 ${LDFLAGS}

thread3: thread3.c
	gcc ${CFLAGS} thread3.c -o thread3 ${LDFLAGS}

thread3a: thread3a.c
	gcc ${CFLAGS} thread3a.c -o thread3a ${LDFLAGS}

thread4: thread4.c
	gcc ${CFLAGS} thread4.c -o thread4 ${LDFLAGS}

thread5: thread5.c
	gcc ${CFLGAS} thread5.c -o thread5 ${LDFLAGS}

thread6: thread6.c
	gcc ${CFLAGS} thread6.c -o thread6 ${LDFLAGS}

thread6a: thread6a.c
	gcc ${CFLAGS} thread6a.c -o thread6a ${LDFLAGS}

thread7: thread7.c
	gcc ${CFLAGS} thread7.c -o thread7 ${LDFLAGS}

thread8: thread8.c
	gcc ${CFLAGS} thread8.c -o thread8 ${LDFLAGS}

thread8a: thread8a.c
	gcc ${CFLAGS} thread8a.c -o thread8a ${LDFLAGS}
