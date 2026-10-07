# QuickSort Pivot Strategy Analysis

An iterative implementation of the QuickSort algorithm in Python to compare the performance of different pivot selection strategies across various dataset configurations.

##  Features
- **Iterative Implementation:** Uses a manual stack to avoid recursion stack overflow.
- **Pivot Strategies:**
  - `FirstPivot`: Uses the first element as the pivot.
  - `LastPivot`: Uses the last element as the pivot.
  - `RandomPivot`: Uses a randomly chosen element as the pivot.
- **Test Scenarios:** Evaluates performance on Increasing, Decreasing, and Randomly shuffled datasets across sizes of 10k, 100k, and 1,000k elements.
- **Metrics:** Measures total swap operations for each algorithm strategy.

##  How to Run
```bash
python quicksort_analysis.py
