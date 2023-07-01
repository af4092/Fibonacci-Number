# [Fibonacci-Number](https://en.wikipedia.org/wiki/Fibonacci_sequence)
Following analyzes and designs an efficient algorithm for finding Fibonacci numbers using dynamic programming.

- In mathematics, the Fibonacci sequence is a sequence in which each number is the sum of the two preceding ones. Numbers that are part of the Fibonacci sequence are known as Fibonacci numbers, commonly denoted Fn. The sequence commonly starts from 0 and 1, although some authors start the sequence from 1 and 1 or sometimes (as did Fibonacci) from 1 and 2. Starting from 0 and 1, the first few values in the sequence are:
```
0, 1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, 144
```
- Following images shows the tailing with squares whose side lengths are successive Fibonacci numbers(1, 1, 2, 3, 5, 8, 13, 21)

<p align="center">
  <img src="https://user-images.githubusercontent.com/24220136/231648700-542473c4-a49c-40c8-8c85-e268989e1d66.png" alt="Image">
</p>

- Variables f0, f1 and f2 store three consecutive Fibonacci numbers in the series:

<p align="center">
  <img src="https://user-images.githubusercontent.com/24220136/231650607-c90c1934-16ea-4d72-aa42-15c0378f9577.png" alt="Image">
</p>

- The Fibonacci sequence first appears in the book Liber Abaci (The Book of Calculation, 1202) by Fibonacci, where it is used to calculate the growth of rabbit populations. Fibonacci considers the growth of an idealized (biologically unrealistic) rabbit population, assuming that: a newly born breeding pair of rabbits are put in a field. Each breeding pair mates at the age of one month, and at the end of their second month they always produce another pair of rabbits. And rabbits never die, but continue breeding forever.

<p align="center">
  <img src="https://user-images.githubusercontent.com/24220136/231649248-ff005949-0320-45e5-bef7-a72fef46145a.png" alt="Image">
</p>

- The algorithm for computing Fibonacci numbers presented here uses an approach known as dynamic programming. Dynamic programming is the process of solving subproblems, then combining the solutions of the subproblems to obtain an overall solution. This naturally leads to a recursive solution. However, it would be inefficient to use recursion, because the subproblems overlap. The key idea behind dynamic programming is to solve each subproblem only once and store the results for subproblems for later use to avoid redundant computing of the subproblems.

- Given java program implements the Fibonacci algorithm and runs the demo as following:

<p align="center">
  <img src="https://user-images.githubusercontent.com/24220136/231650188-e321e2b4-e96d-40eb-b5e9-6f3ba0fd8626.png" alt="Image">
</p>
