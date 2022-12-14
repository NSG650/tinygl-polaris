include ../config.mk

LDFLAGS=-L../src/libTinyGL.a

all:
	$(CC) $(CFLAGS) -I../include $(LDFLAGS) gears.c -o gears

clean:
	-rm gears
