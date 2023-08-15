# Chip-8-Emu
## Simple CHIP-8 emulator written in C++
### Usage
Run:
'./chip8 [filename] [-d/--debug] [-r[width]]'
First argument always has to be a program filename. Additional arguments are:
'-d / --debug'
Debug mode: execute instructions step by step by pressing right arrow. You can also output register values by pressing right control.
'-r[width]'
Choose one of the custom resolution: **640**x320, **1280**x640, **1920**x960 and **2560**x1280.
### Prerequisites
-[SDL 2](https://www.libsdl.org/) library
-make
### Setup
Compile it yourself:
_(On Unix)_
'make'
