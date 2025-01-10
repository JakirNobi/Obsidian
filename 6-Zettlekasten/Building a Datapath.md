2025-01-07 21:19

Status: #active

Tags:[[Datapath Elements]],[[Basic Implementation of Datapath]],[[The Processor->Datapath and Control]],[[Computer Architecture]] 

# Building a Datapath

## Fetching Instructions

![[Screenshot from 2025-01-07 21-17-12.png]]

- Instruction memory (IM) and PC are state elements.
- IM is used to hold and supply instruction given an address
- PC keeps the address of the instructions.
- An adder to increment the PC to the address of the next instruction
## PC working mode

![[Building a Datapath.png]]


## Elements in a basic R-format instruction

![[Building a Datapath-1.png]]


## The Datapath implementation in R-Type

![[Building a Datapath-2.png]]

## R-Type Datapath flow 

![[Building a Datapath-5.png]]


## The other elements for Load and Store

![[Building a Datapath-3.png]]

## Load and store datapath implementation

![[Building a Datapath-4.png]]


## Load and store datapath flow

![[Building a Datapath-6.png]]

## Branch type instruction datapath implementation

![[Building a Datapath-7.png]]


# References