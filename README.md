# ArrayIndexOutOfBoundsException in Java

This repository demonstrates a common Java programming error: an `ArrayIndexOutOfBoundsException` caused by an incorrect loop condition when iterating over an array.

The `bug.java` file contains the erroneous code, which attempts to access an array element beyond its bounds. The `bugSolution.java` file provides the corrected code.

## How to reproduce the bug

1. Compile `bug.java`.
2. Run the compiled code.
3. Observe the `ArrayIndexOutOfBoundsException`.

## Solution

The solution involves modifying the loop condition to ensure that the loop index never exceeds the valid index range of the array.