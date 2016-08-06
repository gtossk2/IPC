all: send read

send: send.o
	gcc send.o -o send -lrt

read: read.o
	gcc read.o -o read -lrt

write.o: write.c
	gcc -c write.c -lrt

read.o: read.c
	gcc -c read.c -lrt

clean:
	rm send send.o read read.o
