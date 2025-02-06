# Julia Function Bug: Incorrect Negative Number Handling

This repository demonstrates a bug in a simple Julia function that incorrectly handles negative numbers.  The function is intended to square the input, but it negates the square of negative inputs.

The `bug.jl` file contains the buggy code, and `bugSolution.jl` provides a corrected version.

## Bug Description

The `myfunction` in `bug.jl` produces unexpected results for negative inputs. Instead of squaring the number and returning a positive value, it squares the number and then negates it. 

## Solution

The corrected function in `bugSolution.jl` addresses this issue by always returning the positive square of the input.