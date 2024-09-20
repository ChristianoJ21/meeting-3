OUTPUT = quadratic_solver
CXX = g++
CXXFLAGS = -Wall -std=c++11 -lm
SRC = quadratice.cpp
all: $(OUTPUT)
$(OUTPUT): $(SRC)
	$(CXX) $(CXXFLAGS) -o $(OUTPUT) $(SRC)
# Clean up the executable and other files
clean:
	rm -f $(OUTPUT)
