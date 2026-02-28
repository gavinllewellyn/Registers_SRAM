# Registers and SRAM Implementation
CIS 310 – Computer Organization  
Assignment 1  

## Implemented Components
- 8-bit General Purpose Registers (R0–R3)
- 8-bit Program Counter with Inc and Load
- 8-bit Instruction Register
- 16x8 Static RAM (SRAM)

## Control Signals
CTRL:
00 - Load
01 - Store
10 - Clear
11 - Set FF

## SRAM Config
- Data Width: 8 bits
- Address Width: 4 bits
- 16 memory locations

## Testing
Tested:
- Store and Load operations
- Clear and Set FF operations
- Address switching via PC and manual input
- Independent address verification

## Author
Gavin Llewellyn
