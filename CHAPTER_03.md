## How divide and conquer approach work?

- Here are the steps involved:
- **Divide**: Divide the given problem into sub-problems using recursion.
- **Conquer**: Solve the smaller sub-problems recursively. If the subproblem is small enough, then solve it directly.
- **Combine**: Combine the solutions of the sub-problems that are part of the recursive process to solve the actual problem.

- Time Complexity of Divide and Conquer Algorithm:

```
   T(n) = aT(n/b) + f(n),
    
    where,
        n = size of input
        a = number of subproblems in the recursion
        n/b = size of each subproblem. All subproblems are assumed to have the same size.
        f(n) = cost of the work done outside the recursive call, which includes the cost of dividing the problem and cost of merging the solutions
```

#### Advantages of Divide and Conquer Algorithm:

- The difficult problem can be solved easily.
- It divides the entire problem into subproblems thus it can be solved parallelly ensuring multiprocessing
- Efficiently uses cache memory without occupying much space
- Reduces time complexity of the problem

##### Disadvantages of Divide and Conquer Algorithm:

- It involves recursion which is sometimes slow
- Efficiency depends on the implementation of logic
- It may crash the system if the recursion is performed rigorously

## Explain master theorem.

<img src="https://github.com/JaydeepAgravat/Analysis-and-design-of-algorithms/blob/main/PNG/3.1.png" width=50%>
<img src="https://github.com/JaydeepAgravat/Analysis-and-design-of-algorithms/blob/main/PNG/3.2.png" width=50%>

## Merge Sort

<img src="https://github.com/JaydeepAgravat/Analysis-and-design-of-algorithms/blob/main/PNG/3.3.png" width=50%>

## Quick Sort

<img src="https://github.com/JaydeepAgravat/Analysis-and-design-of-algorithms/blob/main/PNG/3.4.png" width=50%>

## Multiplying large intergers problem

<img src="https://github.com/JaydeepAgravat/Analysis-and-design-of-algorithms/blob/main/PNG/3.5.png" width=50%>

## Strassen's Matrix Multiplication

<img src="https://github.com/JaydeepAgravat/Analysis-and-design-of-algorithms/blob/main/PNG/3.6.png" width=50%>

<img src="https://github.com/JaydeepAgravat/Analysis-and-design-of-algorithms/blob/main/PNG/3.7.png" width=50%>


