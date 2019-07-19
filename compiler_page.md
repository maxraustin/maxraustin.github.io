## Compiler and Assembler/Virtual Machine

---

### Project Description

---

This project involves two primary programs, which perform as follows:

The compiler takes as input a program written in the KXI language(see grammar below). It performs  
lexical, syntax and semantic analysis on this file, which is then converted into intermediate code.  
The intermediate code is then turned into target code, which is output as an assembly file.  

The assembler takes as input an assembly file, which is parsed and converted into bytecode which   
the virtual machine then executes. The instructions as well as more information can be found below.  

### KXI Language

---

KXI is an object-oriented programming language. Features of the language are described below.

|Supported Primitive Data Types|
|------------------------------|
|Integers                      |
|Characters                    |
|Booleans                      |

* Objects
* Functions
* Function recursion
* Arrays of all primitive types as well as objects

The grammar for the language is included below.


