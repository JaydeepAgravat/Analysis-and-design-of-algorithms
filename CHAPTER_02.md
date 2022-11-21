## Why analysis of algorithms is important? 

- Algorithm analysis is an important part of computational complexity theory, which provides theoretical estimation for the required resources of an algorithm to solve a specific computational problem.
- Analysis of algorithms is the determination of the amount of time and space resources required to execute it.
- To predict the behavior of an algorithm without implementing it on a specific computer.
- More importantly, by analyzing different algorithms, we can compare them to determine the best one for our purpose.
- It is impossible to predict the exact behavior of an algorithm. There are too many influencing factors.
- The analysis is thus only an approximation; it is not perfect.

## Explain: Worst Case, Best Case and Average Case Complexity with suitable example

- Types of Algorithm Analysis:
  - Best case 
  - Worst case
  - Average case

<img src="https://github.com/JaydeepAgravat/Analysis-and-design-of-algorithms/blob/main/PNG/2.1.png" width=50%>
<img src="https://github.com/JaydeepAgravat/Analysis-and-design-of-algorithms/blob/main/PNG/2.2.png" width=50%>

## What is asymptotic notation? 

- Asymptotic notations are the mathematical notations used to describe the running time of an algorithm.
- There are mainly three asymptotic notations:
  1. Big-O notation
  2. Omega notation
  3. Theta notation
- This is also known as an algorithm's GROWTH RATE.
- These are used to characterize the complexity of an algorithms & to compare the performance of two or more algorihtms solving the same problem.

## Time Complexities of all Sorting Algorithms

| Algorithm      | Time Complexity |             |             | Space Complexity |
|----------------|-----------------|-------------|-------------|------------------|
|                |   Best          | Average     | Worst       |       Worst      |
| Selection Sort | Ω(n^2)          | θ(n^2)      | O(n^2)      | O(1)             |
| Bubble Sort    | Ω(n)            | θ(n^2)      | O(n^2)      | O(1)             |
| Insertion Sort | Ω(n)            | θ(n^2)      | O(n^2)      | O(1)             |
| Heap Sort      | Ω(n log(n))     | θ(n log(n)) | O(n log(n)) | O(1)             |
| Quick Sort     | Ω(n log(n))     | θ(n log(n)) | O(n^2)      | O(n)             |
| Merge Sort     | Ω(n log(n))     | θ(n log(n)) | O(n log(n)) | O(n)             |
| Bucket Sort    | Ω(n +k)         | θ(n +k)     | O(n^2)      | O(n)             |
| Radix Sort     | Ω(nk)           | θ(nk)       | O(nk)       | O(n + k)         |
| Count Sort     | Ω(n +k)         | θ(n +k)     | O(n +k)     | O(k)             |
| Shell Sort     | Ω(n log(n))     | θ(n log(n)) | O(n^2)      | O(1)             |
