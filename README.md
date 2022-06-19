# Two-Pass-Assembler-Implementation

Assembler is a program for converting instruction written in low-level assembly code into relocatable machine code and generating along information for the loader. It generates instructions by evaluating the mnemonics in operation field and find the value of symbol and literals to produce machine code. If the assembler does all the work in one scan then it is called single pass assembler, otherwise if it does in multiple scans then it called multi-pass assembler. Here, assembler divides these tasks in two passes:

•	PASS – 1 :
1)	Define symbols and literals and remember them in symbol table and literal table respectively.
2)	Keep track of location counter
3)	Process pseudo-operations

•	Pass – 2 :
1)	Generate object code by converting symbolic op-code into respective numeric op-code
2)	Generate data for literals and look for values of symbols.

An assembler primarily serves as the bridge between symbolically coded instructions written in assembly language and the computer processor, memory and other computational components. An assembler works by assembling and converting the source code of assembly language into object code or an object file that constitutes a stream of zeros and ones of machine code, which are directly executable by the processor.
Assemblers are classified based on the number of times it takes them to read the source code before translating it; there are both single-pass and multi-pass assemblers. Moreover, some high-end assemblers provide enhanced functionality by enabling the use of control statements, data abstraction services and providing support for object-oriented programming structures.

