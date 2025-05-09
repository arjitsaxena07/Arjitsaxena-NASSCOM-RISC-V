# Final Pipeplined RISC V 
Overview
A pipelined RISC-V CPU design uses a multi-stage instruction pipeline to improve throughput by allowing multiple instructions to be processed simultaneously at different stages. This enhances overall CPU performance, especially in high-throughput applications.
Pipeline Stages

# Data Hazards:
RAW (Read-After-Write): Data dependency between instructions.
WAW (Write-After-Write) and WAR (Write-After-Read): Conflicts in register writes and reads.

# Control Hazards:
Result from branch instructions, affecting instruction fetch.
# Structural Hazards:
Resource conflicts, such as competing memory access.

# Hazard Mitigation Techniques
Forwarding: Bypass data from later pipeline stages to earlier stages to resolve data hazards.
Branch Prediction: Predict branch outcomes to reduce control hazards.
Pipeline Stalls: Insert delays to handle data or control hazards.
Out-of-Order Execution: Execute independent instructions in parallel to reduce pipeline gaps.

# RISC-V Specific Features
Fixed Instruction Format: Simplifies instruction fetch and decode.
Load/Store Architecture: Explicit memory operations simplify the MEM stage.
Small Instruction Set: Reduced complexity in the decode stage.

# Key Components
Register File: Stores operands and results, accessed during decode and write-back stages.
ALU: Performs arithmetic and logical operations, handles address calculation in EX stage.
Branch Unit: Evaluates branch conditions in EX stage.
Control Unit: Generates control signals for pipeline management.
Pipeline Registers: Store intermediate data between stages for smooth operation.
Hazard Detection & Forwarding Units: Detect hazards and forward data to prevent stalls.

# Performance Optimization
Superscalar Architecture: Multiple pipelines for parallel instruction processing.
Dynamic Scheduling: Executes independent instructions out of order to reduce pipeline stalls.
Branch Prediction: Advanced predictors to minimize control hazards
Multi-Level Caching: Reduces memory latency and improves instruction/data fetch performance.

## Conclusion
A pipelined RISC-V CPU design increases throughput by overlapping the execution of multiple instructions. While pipelining introduces complexities such as hazard management, techniques like forwarding, branch prediction, and out-of-order execution mitigate these issues and improve performance. The simplicity and modularity of the RISC-V ISA make it ideal for customizable, high-performance CPU designs.


