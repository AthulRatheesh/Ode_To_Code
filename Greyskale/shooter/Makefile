CC=gcc

CFLAGS=-Wall -Werror 
LDFLAGS=-lraylib -lgdi32 -lwinmm

TARGET=main

all : $(TARGET)

$(TARGET) : $(TARGET).c
	$(CC) $(CFLAGS) $< -o $@ $(LDFLAGS)

clean:
		rm -f $(TARGET)