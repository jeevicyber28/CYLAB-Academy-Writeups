# GDB baby step 2

## Platform

picoCTF 2025

## Category

Reverse Engineering

## Difficulty

Medium

## Status

✅ Solved

## Objective

Determine the value stored in the `eax` register at the end of the `main()` function.

## Files Provided

- debugger0_b

## Tools Used

- GDB
- Linux Terminal

## Commands Used

```bash
file debugger0_b
gdb ./debugger0_b
disassemble main
```

## Key Concepts

- GDB Basics
- x86-64 Registers
- Assembly Analysis
- Function Return Values

## What I Learned

- How to inspect the `main()` function using GDB.
- How the `eax` register stores a function's return value.
- How to analyze simple assembly instructions.

## Notes

This challenge helped me understand how to inspect registers and follow program execution using GDB.
