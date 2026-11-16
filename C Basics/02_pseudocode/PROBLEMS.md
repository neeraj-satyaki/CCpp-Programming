# Pseudocode

## Review Workflow
- Problems are listed in increasing difficulty (1-100).
- Solve one problem at a time in this folder (create your own `.c`/notes files as needed).
- When done, add a note/comment: `DONE: <problem number> - awaiting review`.
- I will review your solution. If it is satisfactory and considered a strong answer, proceed to the next problem.
- If not satisfactory, revise the same problem before moving on.
- **Reset policy (requested):** solutions/files in this track may be reset one by one daily to encourage spaced re-practice. Keep backups of work you want to retain.

---

## Problem Statements

1. [Time: 300s (~5m)] Write pseudocode to read an integer and print whether it is positive, negative, or zero.
2. [Time: 370s (~6m 10s)] Write pseudocode to compute the minimum and maximum of three integers using nested conditionals.
3. [Time: 440s (~7m 20s)] Write pseudocode to calculate factorial of N with input validation for negatives.
4. [Time: 510s (~8m 30s)] Write pseudocode to generate first N Fibonacci terms and handle N <= 0.
5. [Time: 580s (~9m 40s)] Write pseudocode to test primality of N using checks up to sqrt(N).
6. [Time: 650s (~10m 50s)] Write pseudocode to count the number of digits in an integer (including 0).
7. [Time: 720s (~12m)] Write pseudocode to compute sum and product of digits of an integer.
8. [Time: 790s (~13m 10s)] Write pseudocode to reverse a string in-place conceptually using indices.
9. [Time: 860s (~14m 20s)] Write pseudocode for linear search that returns all indices of a target value.
10. [Time: 930s (~15m 30s)] Write pseudocode for Euclid's GCD algorithm (iterative).
11. [Time: 1000s (~16m 40s)] Write pseudocode to compute LCM of two numbers using GCD.
12. [Time: 1070s (~17m 50s)] Write pseudocode to convert decimal to binary and store bits in order.
13. [Time: 1140s (~19m)] Write pseudocode to check if a string is a palindrome ignoring case.
14. [Time: 1210s (~20m 10s)] Write pseudocode to find the second largest element in an array.
15. [Time: 1280s (~21m 20s)] Write pseudocode to count frequency of each element in an array.
16. [Time: 1350s (~22m 30s)] Write pseudocode to merge two sorted arrays.
17. [Time: 1420s (~23m 40s)] Write pseudocode for binary search (recursive) and specify base cases.
18. [Time: 1490s (~24m 50s)] Write pseudocode for bubble sort with early-exit optimization.
19. [Time: 1560s (~26m)] Write pseudocode for insertion sort.
20. [Time: 1630s (~27m 10s)] Write pseudocode for selection sort.
21. [Time: 1700s (~28m 20s)] Write pseudocode to remove duplicates from a sorted array in-place.
22. [Time: 1770s (~29m 30s)] Write pseudocode to rotate an array left by K positions.
23. [Time: 1840s (~30m 40s)] Write pseudocode to find GCD of an array of numbers.
24. [Time: 1910s (~31m 50s)] Write pseudocode to check balanced parentheses using a stack.
25. [Time: 1980s (~33m)] Write pseudocode to evaluate a postfix expression.
26. [Time: 2050s (~34m 10s)] Write pseudocode for stack operations using an array with overflow/underflow checks.
27. [Time: 2120s (~35m 20s)] Write pseudocode for circular queue enqueue/dequeue operations.
28. [Time: 2190s (~36m 30s)] Write pseudocode to reverse a linked list iteratively.
29. [Time: 2260s (~37m 40s)] Write pseudocode to detect cycle in a linked list (Floyd's algorithm).
30. [Time: 2330s (~38m 50s)] Write pseudocode for BFS traversal of a graph from a source.
31. [Time: 2400s (~40m)] Write pseudocode for DFS traversal of a graph (recursive).
32. [Time: 2470s (~41m 10s)] Write pseudocode to find shortest path in an unweighted graph using BFS.
33. [Time: 2540s (~42m 20s)] Write pseudocode for Dijkstra's algorithm on a weighted graph.
34. [Time: 2610s (~43m 30s)] Write pseudocode for topological sorting of a DAG.
35. [Time: 2680s (~44m 40s)] Write pseudocode for binary search tree insertion and search.
36. [Time: 2750s (~45m 50s)] Write pseudocode for inorder traversal of a binary tree.
37. [Time: 2820s (~47m)] Write pseudocode to compute height of a binary tree.
38. [Time: 2890s (~48m 10s)] Write pseudocode for Kadane's algorithm (maximum subarray sum).
39. [Time: 2960s (~49m 20s)] Write pseudocode for two-sum using a hash map.
40. [Time: 3030s (~50m 30s)] Write pseudocode for sliding window to find longest substring without repeats.
41. [Time: 3100s (~51m 40s)] Refine pseudocode to include explicit preconditions/postconditions and error codes (builds on #2, difficulty 41/100).
42. [Time: 3170s (~52m 50s)] Extend pseudocode to handle large inputs and integer boundary/overflow considerations (builds on #3, difficulty 42/100).
43. [Time: 3240s (~54m)] Transform iterative pseudocode into a recursive variant with clear base/recursive cases (builds on #4, difficulty 43/100).
44. [Time: 3310s (~55m 10s)] Convert recursive pseudocode to iterative form and compare stack usage (builds on #5, difficulty 44/100).
45. [Time: 3380s (~56m 20s)] Add step-count annotations to pseudocode to reason about time complexity (builds on #6, difficulty 45/100).
46. [Time: 3450s (~57m 30s)] Introduce modular pseudocode by decomposing into named procedures with contracts (builds on #7, difficulty 46/100).
47. [Time: 3520s (~58m 40s)] Adapt pseudocode to work on streaming input where full data cannot fit in memory (builds on #8, difficulty 47/100).
48. [Time: 3590s (~59m 50s)] Design pseudocode that is robust to malformed input and partial failures (builds on #9, difficulty 48/100).
49. [Time: 3660s (~1h 1m)] Optimize pseudocode for fewer passes/memory while preserving correctness (builds on #10, difficulty 49/100).
50. [Time: 3730s (~1h 2m 10s)] Write pseudocode for a capstone mini-system combining parsing, processing, and reporting (builds on #11, difficulty 50/100).
51. [Time: 3800s (~1h 3m 20s)] Refine pseudocode to include explicit preconditions/postconditions and error codes (builds on #12, difficulty 51/100).
52. [Time: 3870s (~1h 4m 30s)] Extend pseudocode to handle large inputs and integer boundary/overflow considerations (builds on #13, difficulty 52/100).
53. [Time: 3940s (~1h 5m 40s)] Transform iterative pseudocode into a recursive variant with clear base/recursive cases (builds on #14, difficulty 53/100).
54. [Time: 4010s (~1h 6m 50s)] Convert recursive pseudocode to iterative form and compare stack usage (builds on #15, difficulty 54/100).
55. [Time: 4080s (~1h 8m)] Add step-count annotations to pseudocode to reason about time complexity (builds on #16, difficulty 55/100).
56. [Time: 4150s (~1h 9m 10s)] Introduce modular pseudocode by decomposing into named procedures with contracts (builds on #17, difficulty 56/100).
57. [Time: 4220s (~1h 10m 20s)] Adapt pseudocode to work on streaming input where full data cannot fit in memory (builds on #18, difficulty 57/100).
58. [Time: 4290s (~1h 11m 30s)] Design pseudocode that is robust to malformed input and partial failures (builds on #19, difficulty 58/100).
59. [Time: 4360s (~1h 12m 40s)] Optimize pseudocode for fewer passes/memory while preserving correctness (builds on #20, difficulty 59/100).
60. [Time: 4430s (~1h 13m 50s)] Write pseudocode for a capstone mini-system combining parsing, processing, and reporting (builds on #21, difficulty 60/100).
61. [Time: 4500s (~1h 15m)] Refine pseudocode to include explicit preconditions/postconditions and error codes (builds on #22, difficulty 61/100).
62. [Time: 4570s (~1h 16m 10s)] Extend pseudocode to handle large inputs and integer boundary/overflow considerations (builds on #23, difficulty 62/100).
63. [Time: 4640s (~1h 17m 20s)] Transform iterative pseudocode into a recursive variant with clear base/recursive cases (builds on #24, difficulty 63/100).
64. [Time: 4710s (~1h 18m 30s)] Convert recursive pseudocode to iterative form and compare stack usage (builds on #25, difficulty 64/100).
65. [Time: 4780s (~1h 19m 40s)] Add step-count annotations to pseudocode to reason about time complexity (builds on #26, difficulty 65/100).
66. [Time: 4850s (~1h 20m 50s)] Introduce modular pseudocode by decomposing into named procedures with contracts (builds on #27, difficulty 66/100).
67. [Time: 4920s (~1h 22m)] Adapt pseudocode to work on streaming input where full data cannot fit in memory (builds on #28, difficulty 67/100).
68. [Time: 4990s (~1h 23m 10s)] Design pseudocode that is robust to malformed input and partial failures (builds on #29, difficulty 68/100).
69. [Time: 5060s (~1h 24m 20s)] Optimize pseudocode for fewer passes/memory while preserving correctness (builds on #30, difficulty 69/100).
70. [Time: 5130s (~1h 25m 30s)] Write pseudocode for a capstone mini-system combining parsing, processing, and reporting (builds on #31, difficulty 70/100).
71. [Time: 5200s (~1h 26m 40s)] Refine pseudocode to include explicit preconditions/postconditions and error codes (builds on #32, difficulty 71/100).
72. [Time: 5270s (~1h 27m 50s)] Extend pseudocode to handle large inputs and integer boundary/overflow considerations (builds on #33, difficulty 72/100).
73. [Time: 5340s (~1h 29m)] Transform iterative pseudocode into a recursive variant with clear base/recursive cases (builds on #34, difficulty 73/100).
74. [Time: 5410s (~1h 30m 10s)] Convert recursive pseudocode to iterative form and compare stack usage (builds on #35, difficulty 74/100).
75. [Time: 5480s (~1h 31m 20s)] Add step-count annotations to pseudocode to reason about time complexity (builds on #36, difficulty 75/100).
76. [Time: 5550s (~1h 32m 30s)] Introduce modular pseudocode by decomposing into named procedures with contracts (builds on #37, difficulty 76/100).
77. [Time: 5620s (~1h 33m 40s)] Adapt pseudocode to work on streaming input where full data cannot fit in memory (builds on #38, difficulty 77/100).
78. [Time: 5690s (~1h 34m 50s)] Design pseudocode that is robust to malformed input and partial failures (builds on #39, difficulty 78/100).
79. [Time: 5760s (~1h 36m)] Optimize pseudocode for fewer passes/memory while preserving correctness (builds on #40, difficulty 79/100).
80. [Time: 5830s (~1h 37m 10s)] Write pseudocode for a capstone mini-system combining parsing, processing, and reporting (builds on #1, difficulty 80/100).
81. [Time: 5900s (~1h 38m 20s)] Refine pseudocode to include explicit preconditions/postconditions and error codes (builds on #2, difficulty 81/100).
82. [Time: 5970s (~1h 39m 30s)] Extend pseudocode to handle large inputs and integer boundary/overflow considerations (builds on #3, difficulty 82/100).
83. [Time: 6040s (~1h 40m 40s)] Transform iterative pseudocode into a recursive variant with clear base/recursive cases (builds on #4, difficulty 83/100).
84. [Time: 6110s (~1h 41m 50s)] Convert recursive pseudocode to iterative form and compare stack usage (builds on #5, difficulty 84/100).
85. [Time: 6180s (~1h 43m)] Add step-count annotations to pseudocode to reason about time complexity (builds on #6, difficulty 85/100).
86. [Time: 6250s (~1h 44m 10s)] Introduce modular pseudocode by decomposing into named procedures with contracts (builds on #7, difficulty 86/100).
87. [Time: 6320s (~1h 45m 20s)] Adapt pseudocode to work on streaming input where full data cannot fit in memory (builds on #8, difficulty 87/100).
88. [Time: 6390s (~1h 46m 30s)] Design pseudocode that is robust to malformed input and partial failures (builds on #9, difficulty 88/100).
89. [Time: 6460s (~1h 47m 40s)] Optimize pseudocode for fewer passes/memory while preserving correctness (builds on #10, difficulty 89/100).
90. [Time: 6530s (~1h 48m 50s)] Write pseudocode for a capstone mini-system combining parsing, processing, and reporting (builds on #11, difficulty 90/100).
91. [Time: 6600s (~1h 50m)] Refine pseudocode to include explicit preconditions/postconditions and error codes (builds on #12, difficulty 91/100).
92. [Time: 6670s (~1h 51m 10s)] Extend pseudocode to handle large inputs and integer boundary/overflow considerations (builds on #13, difficulty 92/100).
93. [Time: 6740s (~1h 52m 20s)] Transform iterative pseudocode into a recursive variant with clear base/recursive cases (builds on #14, difficulty 93/100).
94. [Time: 6810s (~1h 53m 30s)] Convert recursive pseudocode to iterative form and compare stack usage (builds on #15, difficulty 94/100).
95. [Time: 6880s (~1h 54m 40s)] Add step-count annotations to pseudocode to reason about time complexity (builds on #16, difficulty 95/100).
96. [Time: 6950s (~1h 55m 50s)] Introduce modular pseudocode by decomposing into named procedures with contracts (builds on #17, difficulty 96/100).
97. [Time: 7020s (~1h 57m)] Adapt pseudocode to work on streaming input where full data cannot fit in memory (builds on #18, difficulty 97/100).
98. [Time: 7090s (~1h 58m 10s)] Design pseudocode that is robust to malformed input and partial failures (builds on #19, difficulty 98/100).
99. [Time: 7160s (~1h 59m 20s)] Optimize pseudocode for fewer passes/memory while preserving correctness (builds on #20, difficulty 99/100).
100. [Time: 7230s (~2h 0m 30s)] Write pseudocode for a capstone mini-system combining parsing, processing, and reporting (builds on #21, difficulty 100/100).
