# Swift Compiler Error: Missing Argument Labels

This repository demonstrates a common Swift compiler error related to missing argument labels when calling functions.

## Problem

In Swift, functions often have named parameters, which improve code readability and maintainability.  When calling a function, it is essential to use the argument labels unless they are explicitly omitted using the underscore. Omitting labels when they are required causes a compile-time error. 

## Solution

Always use the argument labels when calling a function unless explicitly omitted with an underscore in the function definition.

## How to reproduce the error

1. Clone the repository.
2. Open the `bug.swift` file. You'll see a function `calculateArea` and its incorrect usage.
3. Try to compile the code. The compiler will report an error about missing argument labels.
4. Open `bugSolution.swift` for a corrected version. 

## Lessons Learned

- Understand the importance of argument labels in Swift.
- Pay attention to the compiler errors to help debug your code effectively.
- Be consistent in using argument labels for better code readability and maintainability.