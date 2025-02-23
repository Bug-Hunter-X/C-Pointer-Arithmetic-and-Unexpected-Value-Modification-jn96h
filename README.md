# C Pointer Arithmetic and Unexpected Value Modification

This repository demonstrates a common error in C programming related to pointer arithmetic. The program showcases how modifying a value through a pointer directly affects the original variable. This seemingly simple example highlights the importance of careful pointer handling to avoid unexpected behavior and potential bugs.

## Bug Description

The code modifies a variable's value indirectly through a pointer. While seemingly straightforward, this behavior can be counter-intuitive for beginners and lead to unexpected results or hard-to-debug errors in more complex scenarios.

## How to Reproduce

1. Clone the repository.
2. Compile the `bug.c` file using a C compiler (e.g., GCC): `gcc bug.c -o bug`
3. Run the executable: `./bug`
4. Observe the output, which may differ from the expected result if the user lacks a deep understanding of pointers.

## Solution

The `bugSolution.c` file provides a corrected approach, ensuring better understanding of pointer manipulation in C.
