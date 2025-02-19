# CSS calc() Function Space Error

This repository demonstrates a common error when using the `calc()` function in CSS: forgetting spaces around arithmetic operators.  This often leads to unexpected behavior or parsing errors.

The `bug.css` file contains the incorrect code.  `bugSolution.css` shows the correct implementation.

## How to Reproduce

1. Open `bug.css`.
2. Observe the incorrect usage of `calc()`.
3. Open `bugSolution.css`.
4. See the correct usage with spaces added around the operators.

## Solution

Always ensure there are spaces around the `+`, `-`, `*`, and `/` operators within the `calc()` function.  This ensures correct parsing and expected results.