---
Date: 2025-07-31
Time: 19:56
---
#note #microprocessor #addressingmode #proc80886

Status:[[Completed]]

Tags:[[Microprocessor]],[[Addressing Mode]]


# Addressing Mode
### **1. What is addressing mode? Explain different addressing modes for accessing data in memory with examples.**

**Addressing Mode**  
Addressing mode specifies the way in which the operand of an instruction is accessed. In 8086 microprocessors, various addressing modes are used to access data in memory or registers. Each mode defines a unique method of specifying operands.

**Types of Addressing Modes in 8086:**

1. **Immediate Addressing Mode**
    
    - The operand is a constant within the instruction itself.
        
    - **Example:** `MOV AL, 25H`
        
    - Here, 25H is directly moved to register AL.
        
2. **Register Addressing Mode**
    
    - The operand is located in a register.
        
    - **Example:** `MOV AX, BX`
        
    - The contents of BX are copied to AX.
        
3. **Direct Addressing Mode**
    
    - The memory address is specified directly in the instruction.
        
    - **Example:** `MOV AX, [1234H]`
        
    - AX receives data from memory location 1234H.
        
4. **Register Indirect Addressing Mode**
    
    - The memory address is found in a register (like SI, DI, BX, BP).
        
    - **Example:** `MOV AX, [BX]`
        
    - AX receives data from the memory location pointed to by BX.
        
5. **Based Addressing Mode**
    
    - The effective address is obtained by adding a displacement to the contents of a base register (BX or BP).
        
    - **Example:** `MOV AX, [BX+04]`
        
6. **Indexed Addressing Mode**
    
    - The effective address is the sum of an index register (SI or DI) and a displacement.
        
    - **Example:** `MOV AX, [SI+08]`
        
7. **Based Indexed Addressing Mode**
    
    - Combines a base register, an index register, and an optional displacement.
        
    - **Example:** `MOV AX, [BX+SI+10]`
        
8. **Relative Addressing Mode**
    
    - Used with jump instructions, where the offset is relative to the current value of IP.
        
    - **Example:** `JMP SHORT 20`
        
9. **Implicit Addressing Mode**
    
    - The operand is implied by the instruction.
        
    - **Example:** `CLC` (Clear carry flag)

# References
[ChatGPT](https://chatgpt.com/c/688b478d-9010-800d-9372-97a6ab689933) 