# Reverse

## Platform

picoCTF 2023

## Category

Reverse Engineering

## Difficulty

Medium

## Status

✅ Solved

## Objective

Reverse an ELF binary to recover the password or flag.

## Files Provided

- ret

## Tools Used

- file
- strings

## Commands Used

```bash
file ret
strings -a ret
```

## Key Concepts

- ELF binary analysis
- Static analysis
- Using strings to inspect executables

## What I Learned

- How to identify an ELF executable.
- How to use the `strings` command.
- How to find useful information inside a binary without running it.
