# TypeScript Type Mismatch Bug

This repository demonstrates a common TypeScript error: a type mismatch caused by passing an array to a function expecting a string. The `bug.ts` file contains the erroneous code, while `bugSolution.ts` provides the corrected version.

The bug arises from attempting to pass an array of strings to the `greeter` function, which is designed to accept a single string. TypeScript's type system catches this mismatch during compilation, preventing runtime errors.

The solution involves either modifying the `greeter` function to accept an array or updating the function call to pass a single string.  The solution file demonstrates how to correctly handle this situation.

## How to Reproduce

1. Clone this repository.
2. Compile `bug.ts` using the TypeScript compiler (tsc). You should see a type error.
3. Compile `bugSolution.ts` to see the corrected version.