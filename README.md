# Unexpected Pointer Behavior in C

This repository demonstrates a simple yet subtle bug related to pointer usage in C.  The code appears straightforward, but the behavior might not be what you expect.

## Bug Description
The `bug.c` file contains a program that modifies a variable's value through a pointer. While the code appears to correctly update the variable, there might be unexpected behavior due to compiler optimizations.

## How to Reproduce
1. Clone this repository.
2. Compile `bug.c` using a C compiler (like GCC).
3. Run the executable.

Observe the output. It might vary depending on the compiler and its optimization flags.

## Solution
The `bugSolution.c` file shows a corrected version of the code which avoids the unexpected behavior.