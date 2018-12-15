# Notes about Programming C (3rd Edition)
#### Note to readers on GitHub. This is simply a catalouge of ideas that occur to me as I read. They may or may not make sense or be any help beyond amusement to others than I.

## Chapter 2
#### Assembler vs Compiler
* Assembly language is easier to understand than binary but each instruction
  still has a one to one relationship with a binary instruction. 
* An assembler simply has to translate assembly to machine code.
* Knowing a lang in assembly only allows the programmer to work on one
  processor because of the one to one relationship.
* Higher level languages differ from assembly because:
** They don't rely on a one to one relationship. Many instructions can be
executed from a single function.
** A higher level language works on all or most processors because it gets
compiled through to the proper instructions.

#### Compiling Programs
* Compilers:

** cc
** gcc

* EX:

** gcc program_to_compile.c
** Result: program_to_compile.o - This "o" is for object code.
** Now the program will be linked. This adds any code that was referenced in
your code like a library.
** Finally you get a file with the .out extension. This is an executable.

* The entire process of compiling and linking is **Building**

## Terminology
* **Building**: The entire process of compiling and linking.
 
