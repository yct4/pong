OBJS = main.cpp Game.cpp Game.hpp TextureManager.cpp TextureManager.hpp Map.cpp Map.hpp Ball.hpp Ball.cpp Player.hpp Player.cpp

OBJ_Name = SDLMain

all : $(OBJS)

	g++ $(OBJS) -IC:\Users\nico\Development\x86_64-w64-mingw32\include -L C:\Users\nico\Development\x86_64-w64-mingw32\lib -w -Wl,-subsystem,windows -lmingw32 -lSDL2main -lSDL2_image -lSDL2 -o $(OBJ_Name)
	$(OBJ_Name).exe

clean :
	rm $(OBJ_Name).exe
run :
	$(OBJ_Name).exe

setup-windows:

setup-osx:

build:

.PHONY: build setup-windows setup-osx
