# Github-respiratory-# Laboratory Activity: Recursion

## Brief Description

This program calculates the Greatest Common Divisor (GCD) of two non-negative integers using the recursive Euclidean algorithm.

The program uses a recursive method called `gcdRecursive()` that repeatedly calculates the remainder of `a % b`. The recursion continues until `b` becomes 0, which is the base case. The value of `a` at the base case is the GCD.

The program also displays a recursion trace showing the values used in each recursive call.

## Programming Language Used

Java

## How to Compile and Run

### Compile

Open a terminal or command prompt in the folder containing `RecursiveGCD.java` and enter:

```bash
javac RecursiveGCD.java
