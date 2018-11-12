# CPUSIM
A 8-bit CPU Simulation with Logisim.

## Opcode
The first bit of instruction represent if the operand is Register Identifier or Immediate Value. The next four bit represent the op-code of instruction. Next 3 bits represent identifier of First Register and next 3(8) bits represent Second Register(immediate value).

![16-bit-instr](https://preview.ibb.co/fkJTa0/Untitled-Diagram.png)

1.  ADD - 00001 / 10001 
2.  SUB - 00010 / 10010
3.  JMP - 00011 / 10011
4.  AND - 00100 / 10100
5.  OR  - 00101 / 10101
6.  NOT - 00110 / 10110
7.  XOR - 00111 / 10111
8.  MOV - 01000 / 11000
9.  LOD - 01001 / 11001
10. STR - 01010 / 11010
11. HLT - 11111

## How to run
Open Assembler and write the program in the shell and save the output file.
```bash
python3 assembler.py
```
Open `cpu.circ` module in Logisim simulator, click on RAM and Load Image file generated by assembler. Enable the ticks and program will start execution.

## Author
[Aman Pratap Singh](https://github.com/apsknight)
[Mohnish Reddy](https://github.com/MasterRed97)

## LICENSE
[LICENSE](License)
