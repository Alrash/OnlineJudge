CC=g++
EXE=executor
SOURCES:=$(wildcard *.cpp ../public/*.cpp)
HEADERS:=$(wildcard *.h ../public/*.h)

executor:$(SOURCES) $(HEADERS)
	$(CC) -std=c++11 $(SOURCES) -o $(EXE) `pkg-config glib-2.0 --cflags --libs`
