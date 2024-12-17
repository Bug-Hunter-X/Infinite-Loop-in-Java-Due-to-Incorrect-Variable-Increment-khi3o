# Infinite Loop Bug in Java

This repository demonstrates a common error in Java programming: an infinite loop caused by incorrectly placed increment statements in a loop. 

The `bug.java` file contains the flawed code. The `bugSolution.java` file provides the corrected version.

## Bug Description

The original code attempts to print numbers from 0 to 4. However, due to the placement of the `i++` statement after the `if` condition, the loop variable `i` is not incremented if the condition `i == 5` is met, causing an infinite loop.  The loop will never terminate because the condition `i < 10` will always be true.

## Solution

The corrected code in `bugSolution.java` moves the `i++` statement before the `if` condition, ensuring proper incrementing and loop termination.