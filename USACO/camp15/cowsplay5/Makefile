CXX = g++
CXXFLAGS = -O2 -std=c++0x -Wshadow -Wall -Werror

TARGET = $(notdir $(CURDIR))

all: $(TARGET)

run: $(TARGET)
	time ./$(TARGET)

.PHONY: all clean
