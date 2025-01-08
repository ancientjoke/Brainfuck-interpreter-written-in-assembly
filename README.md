# Brainfuck Interpreter

A simple Brainfuck interpreter written in x86_64 assembly for Linux systems.

## Prerequisites

You need the following tools installed:
- yasm (assembler)
- ld (linker)
- make

On Ubuntu/Debian systems, you can install these with:
```bash
sudo apt-get install yasm make
```
Run make to build the interpreter
```
make
```

Run a Brainfuck program by providing the path to the source file:
```
./bf message.bf
```
