CC = gcc

CFLAGS = -g -W -Wall -Wextra -Wcast-qual -Wno-overlength-strings -Wno-unused-parameter -I../../../csrc/. 

SRC = $(shell ls ../../../csrc/*.c) $(shell ls ../common/*.c ) main.c 

OBJ = $(SRC:.c=.o)

u8g2_utf8: $(OBJ) 
	$(CC) $(CFLAGS) $(LDFLAGS) $(OBJ) -o u8g2_utf8

clean:	
	-rm $(OBJ) u8g2_utf8

