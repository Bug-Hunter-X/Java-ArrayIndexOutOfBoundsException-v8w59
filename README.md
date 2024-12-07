# Java ArrayIndexOutOfBoundsException Bug

This repository demonstrates a common Java programming error: an `ArrayIndexOutOfBoundsException`. The bug arises from an off-by-one error in a loop that iterates over an array.

## Bug Description
The `Bug.java` file contains code that attempts to iterate through an integer array and populate it with even numbers. However, the loop condition is incorrect. This results in an attempt to access an index that is out of bounds, leading to an `ArrayIndexOutOfBoundsException`. 

## Solution
The `Solution.java` file provides a corrected version of the code. The loop condition is adjusted to prevent access beyond the array's bounds. 

## How to reproduce
1. Clone the repository.
2. Compile `Bug.java` using a Java compiler (`javac Bug.java`).
3. Run the compiled code (`java Bug`).  You will observe an `ArrayIndexOutOfBoundsException`.
4. Compile `Solution.java` (`javac Solution.java`).
5. Run the corrected code (`java Solution`). This version will run successfully and print even numbers.