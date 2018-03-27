CXX = g++
#CXXFLAGS = -std=c++11

all: server client

server: server.cpp
	$(CXX) server.cpp -o server

client: client.cpp
	$(CXX) client.cpp -o client

clean:
	rm client server

# these targets do not create any files
.PHONY: clean
# disable built-in rules
.SUFFIXES: