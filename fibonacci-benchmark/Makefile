# header
all: mylib.o 
	gcc -o main_test.exe mylib.o main_test.c

# body 
mylib.o:
	gcc -o mylib.o -c mylib/mylib.c

test:
	gcc -o mylib.o -c mylib/mylib.c
	gcc -o main_test.out main_test.c mylib.o
	./main_test.out

time: 
	gcc -o mylib.o -c mylib/mylib.c  
	gcc -o main_b_time_recursive.out main_b_time_recursive.c mylib.o 
	gcc -o main_b_time_iterative.out main_b_time_iterative.c mylib.o 

space:
	gcc -o mylib.o -c mylib/mylib.c   
	gcc -o main_b_space_iterative.exe main_b_space_iterative.c mylib.o
	gcc -o main_b_space_recursive.exe main_b_space_recursive.c mylib.o
	
clear: 
	rm -rf *.out
	rm -rf *.o
	rm -rf *.exe