trout.o: trout.c trout.h util.h
	gcc -Wall -c trout.c

util.o: util.c util.h
	gcc -Wall -c util.c

main.o: main.c trout.h util.h
	gcc -Wall -c main.c

trout: main.o trout.o util.o
	gcc -Wall main.o trout.o util.o -o trout
