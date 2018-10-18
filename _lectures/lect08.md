---
num: "lect08"
desc: " Number Conversions, arrays, intro to lab04 "
ready: false
pdfurl: /lectures/CS16_Lecture8.pdf
annotatedpdfurl: /lectures/CS16_Lecture8_ann.pdf
annotatedready: true
lecture_date: 2018-10-23
---
# Code from lecture
[https://github.com/ucsb-cs16-s18-mirza/cs16-s18-lectures/tree/master/lec-08](https://github.com/ucsb-cs16-s18-mirza/cs16-s18-lectures/tree/master/lec-08)

## Under the hood of program compilation and execution
* From high-level programs to machine code
    * What are .h, .o and .cpp file?
    * What is an execuatble 
    * Steps in compilation
    * Creating object files and linking programs with g++
* Separate compilation with Makefiles [read about Makefile](https://foo.cs.ucsb.edu/16wiki/index.php/C%2B%2B:_Separate_Compilation_and_Makefiles)
* Compile-time errors
* Linker errors
* Header guards


* Automate the compilation of code from lecture 5 using makefiles

# Topics
This lecture and many of the coming lectures require that we understand how our programs interact with computer memory. This is not required to understanding some of the programming constructs like arrays and pointers but is crucial for reasoning about weird program behavior and debugging. So, we will begin with a model of computer memory and then delve into C++ arrays and pointers


## C++ arrays
* Intro to lab04
* C/C++ arrays are like lists in Python and Arrays in Java. We will discuss the differences between these.
* Declaring and initializing arrays in C++
* Tracing code involving arrays
* Array pitfalls: out of bound array access

