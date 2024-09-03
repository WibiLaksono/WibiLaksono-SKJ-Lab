all: mpy_numbers
mpy_numbers: mpy_numbers.cpp
	g++ -o mpy_numbers mpy_numbers.cpp
dump: mpy_numbers
	objdump -d mpy_numbers > mpy_numbers.asm
clean:
	rm -f mpy_numbers mpy_numbers.asm
run: mpy_numbers
	./mpy_numbers the dependecy rules