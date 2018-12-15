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
* To use the program just type its name and file extension

* The term "loading" refers to loading the program into memory.

## Chapter 3

## Chapter 4
* Variables can begin with and underscore or a letter and then be followed by
  letters, underscores, and numbers.
* Numbers work as you would expect. There are two cool exceptions.
  Integers  preceded by 0 are in octal so 050 (8 * 5) is equivalant to 50 in base
ten.  
  Integers  preceded by 0x or in hex.


## Quick Lookup
* To run: ./<program name>
* If you get an error like this:a.out: No such file or directory, then it probably means the  current directory is not in your PATH.
* To compile with your own name gcc <source.c> -o <name_of_executable>
* Comments: /* */ or //
* Data Types:
  `int`  
  `float`  
  `double`  
  `char`  
  `_Bool`  
* Table 4.1 has a complete list
 
## Terminology
* **Building**: The entire process of compiling and linking.

 
