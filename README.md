# Collatz Conjecture Program

## Background
The Collatz conjecture ( also known as the "3n+1 conjecture") is a conjecture in mathematics that concerns sequences defined by the following algorithm.
<pre><b>Start with any positive integer n. Then each term, called a hailstone, is obtained from 
the previous term as follows: If the previous term is even, the next term is one half of the previous term.
If the previous term is odd, the next term is 3 times the previous term plus 1. The conjecture
is that no matter what positive integer value you start with for n, the sequence will always reach 1.
</b></pre>

## Directions
Write a program that prompts a user to enter a positive integer to begin the algorithm for the Collatz conjecture. The program will use a while loop to print each 
term (hailstone) and make repeated decisions to determine which transformation to apply to each value of the sequence according to the conjecture algorithm until it reaches 1.

## Interface Prototype Example

### Test Case 1 Output
<pre><b>Enter a positive integer to start: 17
The hailstones are: 52, 26, 13, 40, 20, 10, 5, 16, 8, 4, 2, 1,</b></pre>
### Test Case 2 Output
<pre><b>Enter a positive integer to start: 90
The hailstones are: 45, 136, 68, 34, 17, 52, 26, 13, 40, 20, 10, 5, 16, 8, 4, 2, 1,</b></pre>





