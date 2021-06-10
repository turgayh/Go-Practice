## A computer is composed of **four** main part

- The memory unit (MU)
- Arithmetic and logic unit (ALU)
- Input and Output unit (I/OU)
- Control Unit (CU)

## A computer is composed of two types of memory

- The Central Memory
- The Auxiliary Memory

### The Central Memory

This type of memory is necassary to run the operating systems and all the programs your computer will run.The central memory contains two of storage

- **RAM** (Random Access Memory) [Volatile]
- **ROM** (Read-Only Memory) [Non-Volatile]

### The Auxiliary Memory

This type of memory is not volatile. When the power is going off, the data stored will not be erased. Here are some examples of auxiliary memory: Hard drives, USB keys, CD-ROM, DVD ...etc.

## CPU (Central Processing Unit)

The CPU will be responsible for executing the instructions given by a program.

The CPU contains :

- The arithmetic and logic (ALU)
- The control unit

## What is a program ?

To make computers do something , we have to feed them with the precise instructions.This set of instructions is called "program".

## How to speak to the machine?

### Programming languages are formal languages

Instructions that are given to machin are written with programming languages. Programming languages are **formal languages**

- They are two types of programming languages;
  - Low Level
  - High Level

### Machine Language

To speak to the processing unit of computer, we can use a machine language.

### Assembly Language

The assembly language is a **low-level programming language**

```shell
    mov eax , 1
    0x80
```

Note that a.l is different from machine to machine. We say it's **machine-specific**

[](img/assembly.png)
An assembler is used to convert the source files written in an assembly language to object code files. We say that we assemble the program. The linker will then transform those object code files into an executable file. An executable file contains all the computer’s necessary instructions to launch the program.

### High-level languages

## Key takeaways

- At the macro-level, a computer is composed of :

  - A memory unit (MU): to store data and programs

  - An Arithmetic and Logical Unit (ALU): to perform computation

  - An Input and Output Unit (IOU): to manage input devices and output devices.

  - A Control Unit (CU) will manage the MU, ALU, and IOU following the instruction given by the program executed

- CPU means Central Processing Unit (also called processor or microprocessor) is composed of the ALU and CU.

- A program is a set of instructions.

- Developers write programs with a programming language.

- Programming languages are composed of words and characters that must be ordered following specified rules.

- They are high and low-level programming languages.

- Machine language and assembly language are low-level. The instructions written in those languages are closely linked to the hardware organization and capabilities. They provide little abstractions.

- Go is a high-level programming language that is compiled.
