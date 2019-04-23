TestMe.exe: Driver.o BubbleSort.o InsertionSort.o
	g++ Driver.o BubbleSort.o InsertionSort.o  -o TestMe.exe

Driver.o: Driver.cpp
	g++ -c Driver.cpp -o Driver.o

BubbleSort.o: BubbleSort.cpp
	g++ -c BubbleSort.cpp -o BubbleSort.o

InsertionSort.o: InsertionSort.cpp
	g++ -c InsertionSort.cpp -o InsertionSort.o

clean:
	rm -f Driver.o BubbleSort.o InsertionSort.o TestMe.exe

