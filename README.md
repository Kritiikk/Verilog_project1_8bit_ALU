# 8-Bit Arithmetic Logic Unit (ALU)

## Project Overview
This project implements an 8-bit Arithmetic Logic Unit (ALU) using Verilog HDL.  
The ALU performs various arithmetic and logical operations based on a select signal.  
The design is verified using a testbench and simulated in AMD Vivado.



## Features
8-bit ALU design
Supports arithmetic and logical operations
Written in synthesizable Verilog HDL
Testbench included for functional verification
Board-independent (simulation-based)



## Supported Operations

| Select (sel) | Operation |
|-------------|-----------|
| 000 | Addition (A + B) |
| 001 | Subtraction (A - B) |
| 010 | Bitwise AND |
| 011 | Bitwise OR |
| 100 | Bitwise XOR |
| 101 | Bitwise NOT (A) |
| 110 | Left Shift (A << 1) |
| 111 | Right Shift (A >> 1) |



## Module Description

### Inputs
 A[7:0] : 8-bit input operand
 B[7:0] : 8-bit input operand
 sel[2:0] : Operation select signal

### Output
 Y[7:0] : ALU output result


## Tools Used
 Verilog HDL
 AMD Vivado Simulator


## Author
Kriti Kushwaha