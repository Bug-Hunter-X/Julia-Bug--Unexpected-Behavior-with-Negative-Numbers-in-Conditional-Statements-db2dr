# Julia Bug: Unexpected Behavior with Negative Numbers in Conditional Statements

This repository demonstrates an uncommon bug in Julia related to unexpected behavior when handling negative numbers within conditional statements.

The `bug.jl` file contains a function that aims to square its input, returning the positive result regardless of the input's sign.  The function uses `if`, `elseif`, and `else` blocks to achieve this.

However, due to the way negative numbers are handled by the `^` operator in specific conditional contexts, the output is not always as expected.

The `bugSolution.jl` file provides a corrected version of the function, showcasing how to correctly handle negative numbers and obtain the intended output.

## Setup

No special setup is required.  You can run the Julia scripts directly using the Julia REPL.
