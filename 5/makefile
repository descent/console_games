CC=gcc
linux-1: linux-1.o
	$(CC) -o $@ $<
linux-1.o: linux-1.c
	$(CC) -c $<

linux-2: linux-2.o
	$(CC) -o $@ $<
linux-2.o: linux-2.c
	$(CC) -c $<
clean:
	rm -rf *.o linux-1 linux-2
