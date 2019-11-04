# pp
p
poi-36@ubuntu18:~/Desktop/PO/3$ valgrind ./testcplx.o
valgrind: ./testcplx.o: Permission denied
poi-36@ubuntu18:~/Desktop/PO/3$ valgrind ./testcplx.o
valgrind: ./testcplx.o: Permission denied
poi-36@ubuntu18:~/Desktop/PO/3$ chmod 777 -R ~/Desktop/PO/3
poi-36@ubuntu18:~/Desktop/PO/3$ valgrind ./testcplx.o
valgrind: this is not an executable
valgrind: ./testcplx.o: cannot execute binary file


