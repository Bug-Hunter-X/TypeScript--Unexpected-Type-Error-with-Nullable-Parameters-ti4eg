# TypeScript: Unexpected Type Error with Nullable Parameters

This code demonstrates a common issue in TypeScript related to handling nullable parameters.  The `greet` function is designed to accept either a string or null. However, passing `undefined` causes a type error, even though it might seem logically equivalent to null in some contexts.

The solution involves explicitly handling `undefined` in the type definition or within the function's logic.

This repository serves as a simple example of this issue, illustrating the problem and providing a clear solution.