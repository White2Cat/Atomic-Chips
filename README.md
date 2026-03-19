# 🧬 Atomic-Chips

**The Public WebAssembly Operator Armory for Atomic OS.**

## What is Atomic-Chips?
This is the official public operator registry (package repository) for the **Atomic OS** microkernel. 
It houses heavily compressed, pure data-processing chips written entirely in C and forged into `.wasm` binaries.

**No syscalls. No external dependencies. Pure input and output.**

## How to Use
From your Atomic OS host terminal, fetch and install chips directly from the cloud:

```bash
# Example: Fetch the 'filter' operator
> install filter