test: f1.o f2.o
	gcc -o test f1.o f2.o
f1.o: f1.c
	gcc -c -o f1.o f1.c
f2.o: f2.c
	gcc -c -o f2.o f2.c
clean:
	rm *.o test
