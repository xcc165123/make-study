#this is a makefile example
.PHONY: clean
depen=clean main.o
main:$(depen)
	gcc -o main main.o
main.o:main.c
	gcc -c main.c
clean:
	-rm $(depen)