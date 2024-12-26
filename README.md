# Stack Overflow Bug in Hack

This repository demonstrates a common error in recursive functions written in Hack: stack overflow. The `foo` function calculates the factorial of a given integer.  However, when called with a large input, it causes a stack overflow because the recursion depth exceeds the system's limits.  The solution demonstrates how to fix this using iteration instead of recursion.