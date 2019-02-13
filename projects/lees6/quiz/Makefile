CFLAGS = -Wall -fpic -coverage -lm

testme:
	gcc -o testme -g testme.c $(CFLAGS)
	./testme

clean:
	rm -f *.o testme testme.exe *.gcov *.gcda *.gcno