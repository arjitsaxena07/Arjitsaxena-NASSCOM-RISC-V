# Digital Logic With TL Verilog & Makerchip 
## 1) Combinational logic in TL Verilog using Makerchip 
### Lec 1. Introduction to Logic Gates

## *Summary:* 
In this first lecture, I’ve begun exploring the most fundamental part of any digital system—logic gates. These gates are the basic building blocks of digital electronics and perform Boolean operations like AND, OR, and NOT. Even though they look simple at first, they form the foundation of everything from simple decision-making circuits to the complex ALUs and control logic inside modern processors.

![image](https://github.com/user-attachments/assets/885719df-15d2-471d-bc01-898f842466bf)

### Lec 2 Combinational Circuit

## *Summary:* 
In this lecture, I learned about combinational circuits, which are a step up from basic logic gates. These are digital circuits where the output depends only on the current inputs — there's no memory involved, so the behavior is purely input-driven.

Using the logic gates I studied earlier (AND, OR, NOT, XOR, etc.), I built more complex circuits like adders, multiplexers, and comparators. Each of these circuits performs a specific task by combining gates in clever ways.

Here’s what defines a combinational circuit:
1. No clock or timing elements
2. No feedback loops or storage
3. Deterministic output based on current input values

Examples I Explored:
**Half Adder**: Adds two bits and gives a sum and carry output.
**Full Adder**: Handles three bits (two inputs + carry-in).
**Multiplexer**: Selects one of many inputs based on control signals.

## MUX IMPLEMENTATION & INTRO TO MAKERCHIP (https://www.makerchip.com/sandbox/#)

What is Makerchip: Makerchip is one-stop shop for Verilog and TL-Verilog development in your browser as well as simulation visualization for any HDL simulations.

What is MUX: A mux (multiplexer) is a digital switch that selects one input from multiple inputs and forwards it to a single output line based on control signals.

# Implementation: 
![image](https://github.com/user-attachments/assets/83b585c0-1ef3-4509-982a-37f7c9d2f773)

## Lab - Pythagoras Theorem
![image](https://github.com/user-attachments/assets/8eb41c0d-32b7-46aa-8fd4-936b6f702e7f)

## Inverter
![image](https://github.com/user-attachments/assets/ac2370f2-123e-4bc3-9910-87dc7795cfde)

## Boolean 
![image](https://github.com/user-attachments/assets/98e90fee-faa6-43ca-830f-47dd53a753e3)

## Vector 5 BITS 
![image](https://github.com/user-attachments/assets/ac696453-9219-41ef-831f-9dd9ac4a48c6)

## Calculator Design
![image](https://github.com/user-attachments/assets/8e0a3b65-d7d0-41c7-bc49-540fb4011488)

--------------------------------------------------------------------------------------

## **Introduction to Sequential Logic and Counter Lab**

Sequential Logic: Logic circuits where the output depends on current inputs and previous states. It uses memory elements like flip-flops. Common examples: registers, state machines, and counters.

Counters: A type of sequential circuit that goes through a specific sequence of states (usually binary) in response to clock pulses. Types:

Up Counter: Counts upward (e.g., 000 → 001 → 010…)

Down Counter: Counts downward

Up-Down Counter: Can do both

Synchronous: All flip-flops clocked together

Asynchronous: Flip-flops clocked in sequence

These are used in timers, clocks, digital electronics, and embedded systems.

![image](https://github.com/user-attachments/assets/5e157e97-878b-4ba7-9756-74d6c01079d4)

![image](https://github.com/user-attachments/assets/4000279c-a611-4033-a240-a76c8aa265dc)

![image](https://github.com/user-attachments/assets/53ff63bc-cfd4-4968-a0f5-4e8f0f92e1d9)

## Pipelined logic

Pipelined Logic is a technique in digital circuits where a process is divided into multiple stages, each separated by registers, allowing multiple instructions to be processed simultaneously — one in each stage.

# Key Concepts:
Stages: The logic is broken into smaller, manageable parts (e.g., fetch, decode, execute in CPUs).

Registers: Flip-flops store intermediate results between stages.

Clock: A new input is loaded into stage 1 every clock cycle, and previous data moves forward.

# Benefits:
Increases throughput (more operations per time unit)

Efficient hardware usage

Example:
In a 3-stage pipeline:

Clock cycle 1: Instruction 1 in Stage 1

Clock cycle 2: Instruction 1 in Stage 2, Instruction 2 in Stage 1

Clock cycle 3: Instruction 1 in Stage 3, Instruction 2 in Stage 2, Instruction 3 in Stage 1

Common in CPU design, DSPs, and FPGA-based systems for speed optimization.

![image](https://github.com/user-attachments/assets/35469826-2138-4aa8-a819-250fb8168e84)

![image](https://github.com/user-attachments/assets/890cdb25-bb3e-487a-ac82-18f48629c70e)

![image](https://github.com/user-attachments/assets/8df13836-ee23-435c-b3da-94b44b8c0fd4)

## Validity 

Validity refers to how accurately a method, test, or system measures what it is supposed to measure.

# Types of Validity:

# Content Validity: Does it cover all aspects of the concept?

Example: A math test covering all relevant topics.

Construct Validity: Does it truly measure the theoretical concept?

Example: A depression scale that genuinely reflects depression levels.

# Criterion Validity: Does it correlate well with an external standard?

Concurrent: Compared with a current standard.

Predictive: Predicts future outcomes.

Face Validity: Does it seem valid at a glance (not scientifically strong)?

# In Digital Logic:
Validity can also refer to the correctness or expected behavior of signals or operations (e.g., valid output in a timing diagram or protocol).

In short: Validity = correctness + relevance of measurement or operation.

# Lab On Validity And Valid When Condition
![image](https://github.com/user-attachments/assets/11561a3b-781f-47a7-bd42-eb81eab7e4a4)

# Calulator Single Value Memory Lab
![image](https://github.com/user-attachments/assets/c61a6d22-1c81-4985-9509-c5774ef88f1e)

