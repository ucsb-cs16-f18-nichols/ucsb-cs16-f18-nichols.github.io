---
num: "lect11"
desc: "The good, bad and ugly about pointers"
ready: true
pdfurl: /lectures/CS16_Lecture11.pdf
annotatedpdfurl: /lectures/CS16_Lecture11_ann.pdf
annotatedready: true
lecture_date:  2018-11-06
---

## Code from lecture

<https://github.com/ucsb-cs16-f18-nichols/code-from-class/tree/master/11-06>

## Stuff I wrote on the "whiteboard"

<https://1drv.ms/u/s!AlgIeD1urAgmceLrP2wubXSrMVs>


# Topics

The good:

* Pointers allow arrays to be passed to functions efficiently
* Pointers allow arrays of large structs to be traversed effiently

The bad:

* Pointers can only point to one type of data (not generic)
* They don't automatically point - need to do some work

The ugly

* Bugs in code that involves pointers can cause your program to irrecoverably crash (Segmentation fault)
* Examples: dereferencing a null pointer, out of bound array access, dereferncing a pointer that has junk value.

## C++ Memory model
* Barebones model of memory: value vs address
* Scope: local vs. global
* Layout of compiled C++ program in memory: text, global data , heap and stack

