#specify the compiler
CXX=mpic++ -std=c++0x

all: init	
	$(CXX) main.cpp -o bin/main.out

clean:
	rm -rf bin/*	

init:
	mkdir -p bin
	mkdir -p bin/output	

