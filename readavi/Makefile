
FLAGS=-O3 -Wall
#CC=i686-w64-mingw32-gcc

default:
	$(CC) -c fileio.c $(FLAGS)
	$(CC) -o readavi readavi.c fileio.o $(FLAGS)

clean:
	@rm -f readavi
	@rm -f *.o


