all:hello
 
hello : hello.o
	$(CC) $(LDFLAGS) hello.o -o hello -luci 
	
hello.o : hello.c
	$(CC) $(CFLAGS) -Wall -c hello.c
	
clean:
	rm *.o hello