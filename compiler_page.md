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

KXI is an object-oriented programming language. Some features of the language are described below.

|Supported Primitive Data Types|
|------------------------------|
|Integers                      |
|Characters                    |
|Booleans                      |

* Objects
* Functions
* Function recursion
* Arrays of all primitive types as well as objects

The full grammar for the language is included in the file below.

[KXI grammar 2019](/files/KXI_2019.pdf)

---

### Assembler Details

The assembly code used by the virtual machine has the following instructions available to it.

* ADD/SUB/MUL/DIV/ADI : Math operations that use data in registers to perform computations
* LDR/STR/LDB/STB : Load and store operations for ints and chars from registers to memory locations
* MOV : Used to move data between registers
* LDA : Loads a memory address into a registers
* JMP/JMR : Used to jump to locations in memory
* BRZ/BNZ/BLT/BGT : Used to branch to labels in assembly
* AND/OR : Logical instructions
* CMP : Used to compare data in registers
* TRP : Used for I/O and stopping the program.



