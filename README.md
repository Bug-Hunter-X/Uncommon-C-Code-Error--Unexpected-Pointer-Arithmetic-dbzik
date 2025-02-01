# Uncommon C Code Error: Unexpected Pointer Arithmetic

This repository demonstrates a subtle error related to pointer arithmetic in C.  The example highlights how seemingly simple pointer operations can lead to unexpected results if not handled correctly. This is especially relevant when dealing with dynamic memory allocation and array indexing. The solution provides a corrected version and explanation.

## Bug Description

The bug involves incorrect pointer arithmetic that can lead to unexpected program behavior or even crashes if the pointer arithmetic goes outside of allocated memory. The code might seem straightforward, but understanding how pointer arithmetic works at a memory level can prevent this type of error.