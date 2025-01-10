---
Date: 2025-01-10
Time: 21:20
---
Status: [[Completed]] 

Tags:[[Multiplication in Computer]],[[Computer Architecture]],[[Fixed Arithmetic for Computers & ALU Design]] 

# Multiplication using Booth's algorithm

### Rules

1. **Depending on the current and previous bits 00, 11: No arithmetic. 
2. **01: Addition (end of a string of 1 s) : Addition multiplicand to the left half of product.
3. **10: Subtraction multiplicand from the left half of product.
4. **( ) shift right the product register shift right the product register.

### Flowchart

![[Multiplication using Booth's algorithm.png]]

### Example

![[Multiplication using Booth's algorithm-1.png]]


# References
[Online PDF](http://contents2.kocw.or.kr/KOCW/document/2013/soongsil/kimbyounggi1031/7.pdf) 
