# Big O Notation

Big O notation is a mathematical notation used to describe the efficiency of an algorithm, focusing on **time complexity** (how long it takes to run) and **space complexity** (how much memory it uses). It provides an upper bound on the growth rate of an algorithm's resource needs as the input size increases.

## Common Time Complexities

### 1. **O(1) - Constant Time**

- **Example**: Accessing an element in an array by index.
- **Description**: The running time of the algorithm is constant and does not depend on the input size. It takes the same amount of time regardless of how large the input is.

### 2. **O(log n) - Logarithmic Time**

- **Example**: Binary search.
- **Description**: The running time increases logarithmically as the input size grows. Algorithms that divide the problem in half at each step (e.g., binary search) have this complexity.

### 3. **O(n) - Linear Time**

- **Example**: Looping through all elements in an array.
- **Description**: The running time increases linearly with the input size. If the input doubles, the running time also roughly doubles.

### 4. **O(n log n) - Log-Linear Time**

- **Example**: Merge sort, quicksort (average case).
- **Description**: Common in efficient sorting algorithms. The algorithm takes linear time multiplied by a logarithmic factor.

### 5. **O(n²) - Quadratic Time**

- **Example**: Bubble sort, selection sort.
- **Description**: The running time grows quadratically with the input size. Doubling the input size increases the time by four times. This is typical in algorithms with nested loops over the input.

### 6. **O(2ⁿ) - Exponential Time**

- **Example**: Solving the traveling salesman problem via brute force.
- **Description**: The running time doubles with each additional element in the input. Algorithms with this complexity are generally impractical for large inputs.

### 7. **O(n!) - Factorial Time**

- **Example**: Solving the traveling salesman problem via brute force.
- **Description**: The running time grows factorially with the input size. These algorithms are only feasible for very small inputs.

## Big O and Best/Worst/Average Cases

- Big O notation typically describes the **worst-case scenario** for an algorithm. However, some algorithms may have different time complexities for the best, average, and worst cases:
  - **Best case (Ω - Omega notation)**: The minimum time the algorithm can take for any input of size `n`.
  - **Average case (Θ - Theta notation)**: The expected time taken for an input of size `n` over all possible inputs.
  - **Worst case (O - Big O notation)**: The maximum time the algorithm can take for any input of size `n`.
