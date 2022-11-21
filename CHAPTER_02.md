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

## Selection Sort vs Bubble Sort      

| NO | Selection Sort                                                                                                                    | Bubble Sort                                                                                                 |
|----|-----------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------|
| 1. | Selection sorting is a sorting algorithm where we select the minimum element from the array and put that at its correct position. | Bubble sorting is a sorting algorithm where we check two elements and swap them at their correct positions. |
| 2. | Its Time complexity in the Best case is O(N^2)                                                                                    | Its Time complexity in the Best case is O(N)                                                                |
| 3. | Its Time complexity in the worst case is O(N^2)                                                                                   | Its Time complexity in Worst case is O(N^2)                                                                 |
| 4. | This sorting algorithm uses the selection method                                                                                  | This sorting algorithm uses exchanging method                                                               |
| 5. | It is an efficient sorting technique.                                                                                             | It is not an efficient sorting technique.                                                                   |
| 6. | This method is faster.                                                                                                            | This method is slower.                                                                                      |                                                                                   |

## Insertion Sort vs Selection Sort       

| NO  | Insertion Sort                                                                                                                                                                                                          | Selection Sort                                                                                                                                                                                                                                                    |
|-----|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1.  | Inserts the value in the presorted array to sort the set of values in the array.                                                                                                                                        | Finds the minimum / maximum number from the list and sort it in ascending / descending order.                                                                                                                                                                     |
| 2.  | It is a stable sorting algorithm.                                                                                                                                                                                       | It is an unstable sorting algorithm.                                                                                                                                                                                                                              |
| 3.  | The best-case time complexity is Ω(N) when the array is already in ascending order. It have Θ(N2) in worst case and average case.                                                                                       | For best case, worst case and average selection sort have complexity Θ(N2).                                                                                                                                                                                       |
| 4.  | The number of comparison operations performed in this sorting algorithm is less than the swapping performed.                                                                                                            | The number of comparison operations performed in this sorting algorithm is more than the swapping performed.                                                                                                                                                      |
| 5.  | It is more efficient than the Selection sort.                                                                                                                                                                           | It is less efficient than the Insertion sort.                                                                                                                                                                                                                     |
| 6.  | Here the element is known beforehand, and we search for the correct position to place them.                                                                                                                             | The location where to put the element is previously known we search for the element to insert at that position.                                                                                                                                                   |
| 7.  | The insertion sort is used when: The array is has a small number of elements There are only a few elements left to be sorted                                                                                            | The selection sort is used when A small list is to be sorted The cost of swapping does not matter Checking of all the elements is compulsory Cost of writing to memory matters like in flash memory (number of Swaps is O(n) as compared to O(n2) of bubble sort) |
| 8.  | The insertion sort is Adaptive, i.e., efficient for data sets that are already substantially sorted: the time complexity is O(kn) when each element in the input is no more than k places away from its sorted position | Selection sort is an in-place comparison sorting algorithm                                                                                                                                                                                                        |
