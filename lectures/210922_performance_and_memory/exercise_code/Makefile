CC = gcc
CFLAGS = -O3 -Wall

all: cols rows

cols: sum-array-cols.c
	$(CC) $(CFLAGS) -o cols sum-array-cols.c -g

rows: sum-array-rows.c
	$(CC) $(CFLAGS) -o rows sum-array-rows.c -g

clean:
	rm -f rows cols


