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
 chown $poi-36:$poi-36 -R ~/Desktop/PO/3
chown: invalid option -- '3'
Try 'chown --help' for more information.

poi-36@ubuntu18:~/Desktop/PO/3$ chown $USER6:$USER -R ~/Desktop/PO/3

poi-36@ubuntu18:~/Desktop/PO/3$ chown $USER:$USER -R ~/Desktop/PO/3

poi-36@ubuntu18:~/Desktop/PO/3$ valgrind ./testcplx.o
valgrind: this is not an executable
valgrind: ./testcplx.o: cannot execute binary file


