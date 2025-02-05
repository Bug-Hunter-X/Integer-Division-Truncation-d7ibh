# Integer Division Truncation in C

This example demonstrates an issue with integer division in C, where the result is truncated and the fractional part is lost.

## Bug

The code performs integer division between two integers, resulting in the fractional part of the result being ignored.

## Solution

To fix this, we need to use floating-point division. This ensures that the result maintains the fractional part.