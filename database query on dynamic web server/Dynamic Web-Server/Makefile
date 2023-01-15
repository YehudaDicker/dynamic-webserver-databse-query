CC = gcc

# Support externally overriding CFLAGS
CFLAGS ?= -g -Wall -Wpedantic -std=c17
CFLAGS += -I/home/j-hui/cs3157-pub/include

LDFLAGS = -L/home/j-hui/cs3157-pub/lib
LDLIBS = -lmylist

http-server:

.PHONY: clean
clean:
	rm -rf $(TARGETS) main *.o a.out

