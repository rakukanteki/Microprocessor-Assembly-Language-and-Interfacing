# Microprocessor-Assembly-Language-and-Interfacing

### Why Assembly Language:
Assembly Language is a low-level programming language. Understanding programming language helps:

1. How the program interfaces with OS, processor and BIOS.
2. How data is represented in memory and other external devices.
3. How the processor executes and accesses instructions.
4. How instructions access and process data.

### emu 8086:

emu 8086 is a program that emulates an 8086 processor. When we emulate the code written in emu 8086, it shows a binary file. It has some features like:

1. AX, BX, CX, DX, CS, DS, SS, and IP are called registers. Where,
   - AX means Accumulator register. It is of 16 bits and is divided into two 8-bit registers AH and AL to also perform 8-bit instructions. It is generally used for arithmetical and logical instructions.
     
   - BX means Base register. It is of 16 bits and is divided into two 8-bit registers BH and BL to also perform 8-bit instructions. It is used to store the value of the offset.
     
   - CX means Counter register. This is the counter register. It is of 16 bits and is divided into two 8-bit registers CH and CL to also perform 8-bit instructions. It is used in looping and rotation.
     
   - DX means Data register. This is the data register. It is of 16 bits and is divided into two 8-bit registers DH and DL to also perform 8-bit instructions. It is used in the multiplication and input/output port addressing.
  
   - CS means Code segment and IP means Instructions pointer. They can generate the physical address of the memory. They are both 16-bit registers. We cannot access 20-bit locations using 16-bit only. That's why these two 16-bit registers are used to generate physical addresses. Say, when we write a code segment in emu 8086, it saves the code in the code segment. The code segment is dedicated to the program and instructions only. CS provides a segment-based address and IP provides an offset. Both of these registers constitute a 20-bit register. How?
     * CS * 10 + IP
     
   - SS means Stack Segment. Contains data and return addresses.
     
   - DS means Data segment. Contains data, and constants. It is of 16-bit.
     
   - SI means Source Index and DI means Destination Index. These are used for string operations.
     
