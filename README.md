# Chip8_Emulator
Haoyang's First Gander into Emulation.

Hi all, this is (an attempt) to create a Chip-8 Emulator. Chip-8 is a interpreted programming language/virtual machine that is relatively simple and a great starting point for anyone entering the emulation space. Chip-8 was originally designed to make game development easier on very old 8-bit computers like the COSMAC VIP and Telmac 1800. 

A Couple of key specs about the Chip-8:
- It contains only 35 opcodes (instructions)
- Has 4KB of memory (0x000 to 0xFFF), programs start at 0x200
- 16 Registers (V0 to VF)* 
- Index Register (I) used to point towards memory
- Program Counter (16 bit register PC starting at 0x200)
- 16 level deep Stack
- Stack Pointer
- 2 Timers, delay_timer and sound_timer
- Graphics display of 64 x 32 monochrome pixels
