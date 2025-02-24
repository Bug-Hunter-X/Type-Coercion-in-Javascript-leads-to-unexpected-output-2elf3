# Type Coercion Bug in Javascript
This repository demonstrates a common error in Javascript caused by type coercion. When adding a number and a string, the plus operator performs string concatenation instead of numerical addition, leading to unexpected results.

## Bug Description
The `foo` function adds two arguments. However, if one argument is a string and the other is a number, it concatenates them instead of performing numerical addition.

## Solution
The solution involves explicitly converting both arguments to numbers before adding them, ensuring consistent numerical addition. This can be achieved using the `Number()` function.