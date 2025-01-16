# MATLAB Function Bug

This repository demonstrates a common bug in MATLAB functions: incorrect conditional statements leading to unexpected outputs. The function `myFunction.m` contains a logical error in the `if` condition that results in the function returning incorrect values under certain conditions.  The solution is shown in `bugSolution.m`.

## Bug Description

The `myFunction` function is intended to calculate and return a specific value based on an input. However, due to a logical error in the `if` statement, the condition is not evaluated correctly, causing the function to produce incorrect output for certain inputs.

## How to reproduce

1.  Download the files `bug.m` and `bugSolution.m`. 
2.  Open MATLAB and navigate to the directory where you saved the files.
3.  Run `bug.m` with various inputs to observe the unexpected outputs.
4.  Run `bugSolution.m` to see the corrected function.

## Solution

The solution addresses the logical error in the conditional statement, ensuring the function returns the correct output for all input values. The corrected code is in `bugSolution.m`.