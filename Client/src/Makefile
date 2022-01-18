OBJS	= client.o
SOURCE	= client.cpp
HEADER	= 
OUT	= client.out
CC	 = g++
FLAGS	 = -g -c -Wall
LFLAGS	 = -lpthread -lm

all: $(OBJS)
	$(CC) -g $(OBJS) -o $(OUT) $(LFLAGS)

client.o: client.cpp
	$(CC) $(FLAGS) client.cpp -std=c++17


clean:
	rm -f $(OBJS) $(OUT)
