# Part 1: A Quick Introduction

1. Line 9 will print `values added 20`, since `num1` is 10, `num2` is 10, `result` will be 20.
2. Line 13 will print `final result: 20`, since `var` type has no block scope, we can access it at anywhere like outside the if block.
3. Line 9 will print `values added 20`, since `num1` is 10, `num2` is 10, `result` will be 20.
4. Line 13 will have error: `ReferenceError` since `result` is `let` type which is only accessable in the block scope, line 13 is out of block.
5. See #6
6. Both of #5 and #6 will have error: `TypeError: Assignment to constant variable` since `const` type can not be changed.
