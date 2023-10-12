CXX = g++
CXXFLAGS = -Wall

SOURCE = main.cpp
EXECUTABLE = casino_royale

all: $(EXECUTABLE)

$(EXECUTABLE): $(SOURCE)
	$(CXX) $(CXXFLAGS) -o $@ $^

clean:
	rm -f $(EXECUTABLE)

.PHONY: all clean
