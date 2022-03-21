
server: server.o client.o
	gcc server.o -o s
	gcc client.o -o c

server.o: server.c
	gcc -c server.c

client.o: client.c
	gcc -c client.c

clean:
	rm *.o s c
	
