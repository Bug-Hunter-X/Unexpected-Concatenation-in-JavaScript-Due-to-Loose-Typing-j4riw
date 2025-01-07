# Unexpected Concatenation in JavaScript Due to Loose Typing

This code demonstrates a common issue in JavaScript where loose typing leads to unexpected concatenation instead of addition when operating on different data types.

## Bug

The `foo` function intends to add two numbers. However, when one input is a number and the other is a string, JavaScript performs string concatenation instead of numerical addition.

## Solution

The solution involves explicitly converting the inputs to numbers before performing the addition using `Number()` or `parseInt()`.