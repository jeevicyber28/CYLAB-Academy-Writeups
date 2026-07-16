# ASCII FTW

## Platform

picoCTF 2023

## Category

Reverse Engineering

## Difficulty

Medium

## Status

✅ Solved

## Objective

Recover a flag stored as ASCII hexadecimal values in an ELF binary.

## Files Provided

- asciiftw

## Tools Used

- GDB
- objdump

## Commands Used

```bash
file asciiftw
gdb ./asciiftw
disassemble main
```

## Key Concepts

- ASCII values
- Hexadecimal
- Assembly analysis
- ELF binaries

## What I Learned

- How ASCII characters are represented in hexadecimal.
- How to read byte values from assembly.
- How to reconstruct a string from hexadecimal values.
