OBJS = main.cpp

CC = g++

INCLUDE_PATHS = -IC:\vs_dev_libs\SDL\include\SDL2

LIBRARY_PATHS = -LC:\vs_dev_libs\SDL\lib

# -w suppresses all warnings
# -Wl,-subsystem,windows gets rid of the console window
COMPILER_FLAGS = -w -Wl,-subsystem,windows

LINKER_FLAGS = -lmingw32 -lSDL2main -lSDL2

OBJ_NAME = main

all : $(OBJS)
	$(CC) $(OBJS) $(INCLUDE_PATHS) $(LIBRARY_PATHS) $(COMPILER_FLAGS) $(LINKER_FLAGS) -o $(OBJ_NAME)

clean:
	del main.exe
 
run:
	main.exe