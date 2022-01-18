OBJS	= server.o
SOURCE	= server.cpp
HEADER	= 
OUT	= server.out
CC	 = g++
FLAGS	 = -g -c -Wall
LFLAGS	 = -lpthread -lm

all: $(OBJS)
	$(CC) -g $(OBJS) -o $(OUT) $(LFLAGS)

server.o: server.cpp
	$(CC) $(FLAGS) server.cpp -std=c++17


clean:
	rm -f $(OBJS) $(OUT)
