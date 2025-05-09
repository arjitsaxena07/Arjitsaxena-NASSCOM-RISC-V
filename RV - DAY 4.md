#  RISC-V CPU micro-architecture

RISC-V micro-architecture defines the internal design of a CPU that follows the RISC-V instruction set. It includes components like:

- Instruction Fetch Unit: Gets the next instruction from memory.
-Decode Unit: Decodes instruction and generates control signals.
-Register File: Holds 32 general-purpose registers.
-ALU: Performs arithmetic and logical operations.
-Memory Access Unit: Handles load/store operations.
-Write-back Unit: Stores results back to registers.
-Control Unit: Manages data paths and operation flow.

## It can be implemented as:

Single-cycle: One instruction per cycle (simple, slow).
Multi-cycle: Splits instruction across cycles (efficient).
Pipelined: Overlaps instruction stages (fast, complex).
RISC-V's open standard makes it ideal for education and custom CPU design.

## L1. Micro-architecture of Single Cycle RISC-V CPU
-Executes one instruction per clock cycle.
-Main components: Instruction Memory, Register File, ALU, Data Memory, Control Unit.
-All operations (fetch, decode, execute, memory access, write-back) occur in one cycle.
-Simpler design, faster to understand but inefficient at scale due to long critical path.

## L2. Starting Point Code for RISC-V
-Provides a basic Verilog/VHDL template for implementing a simple RISC-V CPU.
-Includes modules for ALU, control logic, register file, and memory.
-Useful for learning instruction execution flow and for modifying or extending the CPU.

## LAB PART 1: 
![image](https://github.com/user-attachments/assets/3ed8c34b-ad03-47ac-bbec-fa00c24d31bd)

## LAB PART 2: 
![image](https://github.com/user-attachments/assets/c26f8b9f-3a79-4a38-b7bb-253be064b43e)

## LAB PART 3:
![image](https://github.com/user-attachments/assets/79d1ff52-b8e0-47b8-a6b3-56652d26127b)

# FETCH & CODE
![image](https://github.com/user-attachments/assets/39385206-77e6-4f15-8b93-bc470eccaef2)

![image](https://github.com/user-attachments/assets/cd903a7b-e38d-4bb9-a9f8-69dc185205b4)

![image](https://github.com/user-attachments/assets/9bc8d56d-5528-4f2d-9890-5f804117197d)

![image](https://github.com/user-attachments/assets/f3a07c5b-8b8e-46f5-b8b5-09ea6b75917e)

# RISC-V control logic

## PART 1: 
![image](https://github.com/user-attachments/assets/1b9c3a02-a0e6-458a-a7bb-79b0b4cb8cb8)

## PART 2: 
![image](https://github.com/user-attachments/assets/6ff6e1de-281a-4321-b3b7-3cb841a52d92)


