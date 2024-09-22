OUTPUT = largest_number
CXX = g++
CXXFLAGS = -Wall -std=c++11 -lm
SRC = largest.cpp
all: $(OUTPUT)
$(OUTPUT): $(SRC)
	$(CXX) $(CXXFLAGS) -o $(OUTPUT) $(SRC)
test: $(OUTPUT)
	./$(OUTPUT) test
clean:
	rm -f $(OUTPUT)
.PHONY: all clean test
