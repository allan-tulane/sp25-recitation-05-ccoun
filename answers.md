# CMPS 2200 Reciation 5
## Answers

**Name:** Charlie Coun


Place all written answers from `recitation-05.md` here for easier grading.

|   n |   qsort-fixed-pivot |   qsort-random-pivot |   ssort |   tim-sort |
|-----|---------------------|----------------------|---------|------------|
|  10 |               0.007 |                0.005 |   0.086 |      0.000 |
|  20 |               0.011 |                0.011 |   0.127 |      0.001 |
|  30 |               0.015 |                0.019 |   0.201 |      0.001 |
|  40 |               0.020 |                0.022 |   0.275 |      0.001 |
|  50 |               0.028 |                0.033 |   0.358 |      0.002 |
|  60 |               0.031 |                0.040 |   0.446 |      0.002 |
|  70 |               0.039 |                0.048 |   0.557 |      0.003 |
|  80 |               0.051 |                0.056 |   0.741 |      0.004 |
|  90 |               0.098 |                0.065 |   0.854 |      0.004 |
| 500 |               0.366 |                0.407 |   9.815 |      0.025 |



- **1b.**
Through the tests performed and the table given above, we can see that either version of quick sort, fixed or pivot, will always be faster than selection sort, especially when n grows large enough. As n increases, selection sort shows quadratic growth, so it has a bound of O(n^2). When comparing fixed pivot and random pivot quick sort, on most values of n we can see that fixed pivot grows slower and typically takes less time than random, but on specific occurences such as n = 10 or n = 90, we see that fixed actually takes more time, since it has a worst case complexity of O(n^2), while random only has O(nlogn).



- **1c.**
We can see through the graph that tim sort is by far the fastest and most efficient as n grows larger, since it has a best case complexity of about O(n), which is much more optimal than the other three.
