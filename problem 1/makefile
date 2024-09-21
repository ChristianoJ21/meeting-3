OUTPUT = quadratic_solver
CXX = g++
CXXFLAGS = -Wall -std=c++11 -lm
SRC = quadratice.cpp
all: $(OUTPUT)
$(OUTPUT): $(SRC)
	$(CXX) $(CXXFLAGS) -o $(OUTPUT) $(SRC)
test: $(OUTPUT)
	./$(OUTPUT) test
clean:
	rm -f $(OUTPUT)
.PHONY: all clean test
