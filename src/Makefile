CXXFLAGS=-I./include -isystem /usr/include/GL
LDFLAGS=-lglut -lGL -lGLU

all: tetrix

tetrix: Main.o Color.o Tetris.o
	$(CXX) $(CXXFLAGS) $(LDFLAGS) $^ -o $@
