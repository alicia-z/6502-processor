# 6502 Processor

Created using [Digital](https://github.com/hneemann/Digital/tree/master), a digital logic designer and simulator. This project mimics a subset of the original 6502 Processor.

## Milestones

Files prefixed with a number are each of the milestones; the rest are various subcircuits.

### Milestone 1
Arithmetic Logic Unit - various operations implemented through subcircuits.

### Milestone 2
Buses (D and B) - information is outputted onto a bus via drivers, whose pins were connected to their corresponding control lines. ALU is also implemented into this circuit. 

### Milestone 3
Processor Status Register - register which holds flags for the ALU (Carry, Overflow, Zero, Negative).

### Milestone 4
Processor Infrastructure - connects buses to interface. ADL (Address Bus High) and ADH (Address Bus Low) take data from the buses to the RAM and ROM in the interface.

### Milestone 5
Program Counter - holds the address of the current or next position of the program in RAM.

### Milestone 6
Processor Interface - control center. Control lines can be set by the user to control what the processor does. Opcodes from the RAM are used to call instructions from ROM, which then take over the control lines.

### Notes
Control lines 72-74 are unused, as they were not explained in the document.
The values for the ROM chips are not given, so nothing is encoded into the chips. The opcodes for the RAM (Milestone 7) are also left blank.

## Resources 
[Instruction set](https://www.masswerk.at/6502/6502_instruction_set.html)

[Opcodes](http://www.6502.org/tutorials/6502opcodes.html)

[Hanson's Block Diagram](https://www.witwright.com/DonPub/6502-Block-Diagram.pdf)

