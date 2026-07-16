# GDB baby step 3

## Platform

picoCTF 2025

## Category

Reverse Engineering

## Difficulty

Medium

## Status

✅ Solved

## Objective

Inspect memory after a value is loaded and identify the bytes stored in memory.

## Files Provided

- debugger0_c

## Tools Used

- GDB
- Linux Terminal

## Commands Used

```bash
gdb ./debugger0_c
disassemble main
b *0x40111c
run
x/4xb $rbp-4
```

## Key Concepts

- GDB breakpoints
- Memory inspection
- Endianness
- x86-64 assembly

## What I Learned

- How to set a breakpoint in GDB.
- How to inspect memory using `x/4xb`.
- How little-endian systems store bytes in memory.
- How to interpret memory values for reverse engineering challenges.
