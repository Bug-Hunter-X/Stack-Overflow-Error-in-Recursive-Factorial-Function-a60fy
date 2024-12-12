# Stack Overflow Error in Recursive Factorial Function

This repository demonstrates a common error in recursive functions: stack overflow. The `foo` function calculates the factorial of a number using recursion.  For large inputs, the recursive calls will exceed the maximum stack depth, resulting in a runtime error.

The solution demonstrates how to calculate the factorial iteratively, avoiding the stack overflow issue.

## Bug

The `bug.hack` file contains the recursive factorial function that causes the stack overflow.

## Solution

The `bugSolution.hack` file presents a corrected iterative implementation of factorial which avoids this problem.
