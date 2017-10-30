PS: input.c
	gcc input.c -o input -g -lm -Wall 
	
SOURCE = input.c
PROGRAM = input
CFLAGS = -g -lm -Wall -pedantic
INPUT = 12.323 3242.432 10E78

main: ${SOURCE}
	gcc ${SOURCE} -o ${PROGRAM} ${CFLAGS}
	
run: ${PROGRAM}
	./${PROGRAM} ${INPUT} > ../output.txt

open:
	#open -a Sublime\ Text program.c makefile
	open ${SOURCE} makefile README.md

clean: 
	rm -rf *.o *.out ${PROGRAM}

clear:
	clear
	clear

help:
	#commands main, run, open, clean, clear, help
#files program.c makefile README.md
