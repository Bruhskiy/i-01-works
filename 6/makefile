main: main.o island.o
	gcc main.o island.o -o island.exe

main.o: main.c island.h
	gcc -c main.c

island.o: island.c island.h
	gcc -c island.c