# unpackme.py

## Platform

picoCTF 2022

## Category

Reverse Engineering

## Difficulty

Medium

## Status

✅ Solved

## Objective

Analyze an encrypted Python script and recover the hidden flag.

## Files Provided

- unpackme.flag.py

## Tools Used

- Python 3

## Commands Used

```bash
cat unpackme.flag.py
python3 unpackme.flag.py
```

## Key Concepts

- Python source analysis
- Fernet encryption
- exec()
- Static code analysis

## What I Learned

- How encrypted Python code can be decrypted at runtime.
- Why using `print(plain.decode())` helps inspect hidden code.
- How to analyze Python programs without blindly executing them.
