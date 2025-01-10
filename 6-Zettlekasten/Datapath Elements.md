2025-01-07 20:58

Status: #completed

Tags:[[Computer Architecture]],[[Datapath Elements]],[[The Processor->Datapath and Control]] 

# Datapath Elements
- **ALU** – one or more to carry out the computation. ALU is not only used in data operations but also in address calculation too.

- **Instruction Register and decoder** – to decode what instruction to be executed and how to execute the instruction.

- **Program Counter** – Always points to the next instruction to be executed and manages the flow of instructions.

- **Memory -**

1. Instruction memory is mostly read-only in the fetch phase.
2. Data memory is required to access the operand and result writing.
3. The memory is accessed over a bus from the CPU.
4. To access memory, the address of the memory location is required in addition to Read/Write of data.
5. The Memory Address Register (MAR) holds the address of the memory location to be accessed.
6. The Memory Data Register (MDR) holds the data. It holds the data read from memory (Data-in) in the case of memory read; holds the data to be written into the memory location in the case of Memory write operations. Thus MDR is a bidirectional register.

- **Registers** – Registers are in physical proximity and internal to the CPU. These are ultra-fast than Memory.Most of the times the operands are brought from memory and kept in registers. Rather these registers are used as a workspace and rough space for workout.
- **Register files** – These are multiport register set enabling faster and parallel access to the register set.
- **Internal Registers** –   Instruction Register, Memory Address Register, Memory Data Register. These are not accessible to the programmer.
- **Multiplexers** – Anything is reachable with these. These allow what is to be allowed out based on the selection input.
- **Internal bus** – which connects all these elements.
- **Control unit** – the master which manages the datapath elements.

 
# References

[Online PDF](https://elearning.unimib.it/pluginfile.php/1241149/mod_resource/content/1/Cap5_Datapath.pdf) 