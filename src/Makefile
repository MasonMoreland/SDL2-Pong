all: pong.exe

pong.exe: pong.cpp util.hpp pong.hpp
	g++ -O1 --std=c++11 pong.cpp -lSDL2 -lSDL2_image -lSDL2_ttf -lm -o pong.exe `sdl2-config --prefix=$(HOME)/usr --cflags --libs` -I$(HOME)/usr/include

clean:
	rm -f pong.exe
