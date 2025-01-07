# F# Mutability Bug

This example demonstrates a common error in F#: attempting to modify a variable declared with `let` without making it mutable.  F# emphasizes immutability, so this leads to a compiler error.

The `bug.fs` file contains code that attempts this modification. The `bugSolution.fs` demonstrates the correct approach using the `mutable` keyword.

## How to reproduce

1. Copy the contents of `bug.fs` into an F# file.
2. Attempt to compile and run the code.  You will receive a compiler error.
3.  Refer to `bugSolution.fs` to see the corrected version.