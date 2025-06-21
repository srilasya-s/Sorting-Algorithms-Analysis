This is analysis on how fast each sorting algorithm perform in different complexities.
This experiment also determines the behaivour of algorithm.
Here,
First letter: Algorithm (S: Selection, I: Insertion, M: Merge, Q: Quick)

Second letter: Data case (C: Constant, S: Sorted, R: Random)

Algorithm Analysis:

Selection Sort
Theoretical Complexity: Θ(n²) for all cases

Empirical Results:

Consistent quadratic behavior across constant, sorted, and random data

n² ratios closely match theoretical expectations

Matches theoretical complexity in all scenarios

Insertion Sort
Theoretical Complexity:

Best case: Ω(n) (already sorted data)

Average/Worst case: Θ(n²)

Empirical Results:

Linear behavior for constant and sorted data (best case)

Quadratic behavior for random data (average case)

Matches theoretical expectations for all cases

Merge Sort
Theoretical Complexity: Θ(n log n) for all cases

Empirical Results:

Consistent n log n behavior across all data cases

Ratios align with theoretical predictions

Matches theoretical complexity in all scenarios

Quick Sort
Theoretical Complexity:

Best/Average case: Θ(n log n)

Worst case: O(n²) (poor pivot selection)

Empirical Results:

Quadratic behavior for constant data (worst case - QC)

n log n behavior for sorted and random data (QS, QR)

Matches theoretical expectations:

Worst-case behavior with constant data

Best/average-case behavior with sorted/random data

Conclusion
All empirical results align with theoretical complexities:

Selection Sort consistently demonstrates quadratic behavior

Insertion Sort shows best-case linear and average-case quadratic performance

Merge Sort maintains n log n efficiency across all cases

Quick Sort exhibits both best-case (n log n) and worst-case (n²) behavior depending on input data
