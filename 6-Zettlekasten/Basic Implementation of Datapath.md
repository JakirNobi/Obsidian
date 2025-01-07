2025-01-07 20:54

Status:

Tags:[[Computer Architecture]],[[The Processor->Datapath and Control]]

# Implementation of Datapath

For every instruction, the first two steps are identical:

1. Sent the PC to the memory that contains the code and fetch the instruction from that memory.
2. Read one or two registers, using fields of the instruction to select the registers to read.

All instruction classes use the ALU after reading the registers.
- Memory-reference – address calculation
- Arithmetic-logic – operation execution
- Branch – comparison.

# References