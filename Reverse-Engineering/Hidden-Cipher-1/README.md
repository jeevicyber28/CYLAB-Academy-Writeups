# Hidden Cipher 1

## Platform
CYLAB Academy

## Category
Reverse Engineering

## Difficulty
Medium

## Objective

Find the hidden encryption key and decrypt the flag.

## Tools Used

- file
- strings
- upx
- gdb
- objdump

## Commands

```bash
file hiddencipher
strings hiddencipher
upx -d hiddencipher
gdb ./hiddencipher
objdump -t hiddencipher
```

## What I Learned

- How to unpack a UPX binary
- How to use GDB
- How XOR encryption works
- How to analyze ELF binaries

## Notes

This challenge helped me understand binary analysis and XOR-based encryption.
