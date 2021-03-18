# assignment

* The project in on "Compiling multiple source files into a single executable", in which a "Reverse Polish Calculator" has been made in C language with Vim editor in Ubuntu through Terminal.
* The source codes are seperated into headers and implementations.
* The header file is named "calc.h".
* The implementations files are named "main.c", "getop.c", "stack.c", "getch.c".
* All the files must kept in the same directory.
* Each C file have to be compiled to get object file and then all the object files must be linked up to get an executable file. As more instruction have to given through terminal, it's not so good to compile files one by one..
* There is a instruction file added named "makefile".Which will automatically compile all files to do this easily.
* In the instruction file, at first defined CFLAGS = -O (optimization) , CC = gcc , then instruction to make object file from all the C files, here the name of the executable file can be given, in this project the executable file name is "CalcTest". Then define the C file from which the object file will be make for every C file one by one. At the end there are a instruction "clean" defining the all object file can be remove after execution if the command given named "clean".
* Then everything is ready, just a command have to be given is "make" in the terminal, this will compile all the files and make an executable file which run the program.

