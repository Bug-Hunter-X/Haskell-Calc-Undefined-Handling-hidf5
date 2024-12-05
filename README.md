# Haskell Undefined Value Bug

This repository demonstrates a common error in Haskell programming: attempting to use an undefined value in a calculation.  The `undefined` value represents a computation that hasn't been given a concrete value. Trying to perform operations with it leads to a runtime exception.

The `bug.hs` file contains the problematic code. The `bugSolution.hs` file shows how to correct it by providing a proper value or handling potential undefined values using pattern matching or maybe monad.

This is a simple but illustrative example of the importance of careful type handling and data definition in Haskell to avoid runtime errors.