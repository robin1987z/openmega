OBJS = src/*cpp
DEPS = inc/

CC = g++ 

COMPILER_FLAGS = -w -I$(DEPS)

LINKER_FLAGS = -g -lm -lSDL2 -lSDL2_image -lSDL2_ttf -lSDL2_net -std=c++11

all : $(OBJS)
	$(CC) $(OBJS) $(COMPILER_FLAGS) $(LINKER_FLAGS) -o exec
