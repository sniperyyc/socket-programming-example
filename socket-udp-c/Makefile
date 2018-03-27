CXX = gcc

all: server client

server: server.c
	$(CXX) server.c -o server

client: client.c
	$(CXX) client.c -o client

clean:
	rm client server

# these targets do not create any files
.PHONY: clean
# disable built-in rules
.SUFFIXES: