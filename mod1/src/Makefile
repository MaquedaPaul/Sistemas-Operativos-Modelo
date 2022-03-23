CC = gcc
OUTFILE = mod1.out

SRC = $(shell find ./src -type f -iname "*.c" -exec basename {} \;)
OBJ = 

build: makefolder
	$(CC) -o $(OUTFILE) main.c $(OBJ) $(SHARED)



makefolder:
	if [ ! -d ./obj ] then mkdir obj; fi