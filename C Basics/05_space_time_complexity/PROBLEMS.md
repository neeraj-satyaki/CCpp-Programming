# Space and Time Complexity

## Review Workflow
- Problems are listed in increasing difficulty (1-100).
- Solve one problem at a time in this folder (create your own `.c`/notes files as needed).
- When done, add a note/comment: `DONE: <problem number> - awaiting review`.
- I will review your solution. If it is satisfactory and considered a strong answer, proceed to the next problem.
- If not satisfactory, revise the same problem before moving on.
- **Reset policy (requested):** solutions/files in this track may be reset one by one daily to encourage spaced re-practice. Keep backups of work you want to retain.

---

## Problem Statements

1. [Time: 300s (~5m)] Measure how runtime of a simple loop grows for N = 10^3..10^7 (conceptual or timed).
2. [Time: 370s (~6m 10s)] Analyze time/space complexity of computing sum 1..N using loop vs formula.
3. [Time: 440s (~7m 20s)] Implement linear search; count comparisons for best/average/worst cases.
4. [Time: 510s (~8m 30s)] Implement binary search; prove O(log N) comparisons.
5. [Time: 580s (~9m 40s)] Compare recursive vs iterative factorial in time and stack space.
6. [Time: 650s (~10m 50s)] Analyze naive recursive Fibonacci and count recursive calls for small N.
7. [Time: 720s (~12m)] Implement Fibonacci with memoization; analyze time/space improvement.
8. [Time: 790s (~13m 10s)] Implement Fibonacci iteratively with O(1) space.
9. [Time: 860s (~14m 20s)] Bubble sort: derive best/worst time and space; demonstrate with input cases.
10. [Time: 930s (~15m 30s)] Selection sort: analyze comparisons/swaps independent of input order.
11. [Time: 1000s (~16m 40s)] Insertion sort: analyze best case (nearly sorted) vs worst case.
12. [Time: 1070s (~17m 50s)] Merge sort: derive O(N log N) time and O(N) space; trace recursion tree idea.
13. [Time: 1140s (~19m)] Quick sort: best/average/worst cases and space due to recursion.
14. [Time: 1210s (~20m 10s)] Counting sort: analyze when O(N+K) is efficient; space trade-off.
15. [Time: 1280s (~21m 20s)] Binary search on answer: analyze complexity for a sample feasibility problem.
16. [Time: 1350s (~22m 30s)] Hash table average vs worst-case lookup; discuss collision impact.
17. [Time: 1420s (~23m 40s)] Analyze complexity of checking duplicates using nested loops vs hash set.
18. [Time: 1490s (~24m 50s)] Two-pointer technique for pair sum in sorted array: analyze complexity.
19. [Time: 1560s (~26m)] Sliding window for fixed/variable window problems: analyze amortized behavior.
20. [Time: 1630s (~27m 10s)] Compute prefix sums: preprocessing and query time/space trade-offs.
21. [Time: 1700s (~28m 20s)] Analyze space complexity of adjacency matrix vs adjacency list for sparse/dense graphs.
22. [Time: 1770s (~29m 30s)] BFS time/space complexity in terms of V and E.
23. [Time: 1840s (~30m 40s)] DFS time/space complexity including recursion stack.
24. [Time: 1910s (~31m 50s)] Dijkstra with array vs binary heap: complexity comparison.
25. [Time: 1980s (~33m)] 0/1 knapsack DP: time/space and space-optimized variant.
26. [Time: 2050s (~34m 10s)] LCS DP table: time/space and reconstruction cost.
27. [Time: 2120s (~35m 20s)] Analyze recursive backtracking (permutations/N-Queens) complexity bounds.
28. [Time: 2190s (~36m 30s)] String concatenation in loops: complexity pitfalls and efficient alternatives.
29. [Time: 2260s (~37m 40s)] Amortized analysis: dynamic array (vector) push_back growth strategy.
30. [Time: 2330s (~38m 50s)] Analyze complexity of union-find with/without path compression and union by rank.
31. [Time: 2400s (~40m)] Find kth smallest: sort vs heap vs quickselect complexities.
32. [Time: 2470s (~41m 10s)] Analyze memory layout/cache effects conceptually for array vs linked list traversal.
33. [Time: 2540s (~42m 20s)] Tail recursion: can compiler optimize? discuss space implications in C.
34. [Time: 2610s (~43m 30s)] Compare in-place vs out-of-place algorithms with examples.
35. [Time: 2680s (~44m 40s)] Analyze complexity of building a heap and performing heap sort.
36. [Time: 2750s (~45m 50s)] Multi-key sorting (sort by A then B): stability and complexity considerations.
37. [Time: 2820s (~47m)] External sorting: analyze I/O complexity when data exceeds RAM.
38. [Time: 2890s (~48m 10s)] Time-space trade-off in memoization vs tabulation for a chosen DP problem.
39. [Time: 2960s (~49m 20s)] Analyze complexity of string matching: naive vs KMP vs Rabin-Karp (avg/worst).
40. [Time: 3030s (~50m 30s)] Capstone analysis: choose best algorithm for a workload given constraints and justify with Big-O, constants, and memory.
41. [Time: 3100s (~51m 40s)] Complexity L41: Derive tight bounds and identify dominant terms (extends concept from #1).
42. [Time: 3170s (~52m 50s)] Complexity L42: Provide best/average/worst-case analysis with example inputs (extends concept from #2).
43. [Time: 3240s (~54m)] Complexity L43: Compare alternative algorithms and justify selection (extends concept from #3).
44. [Time: 3310s (~55m 10s)] Complexity L44: Empirically benchmark and relate results to theoretical complexity (extends concept from #4).
45. [Time: 3380s (~56m 20s)] Complexity L45: Optimize space while maintaining asymptotic time (extends concept from #5).
46. [Time: 3450s (~57m 30s)] Complexity L46: Analyze recursion depth/stack usage and risk of overflow (extends concept from #6).
47. [Time: 3520s (~58m 40s)] Complexity L47: Consider cache/locality and constant factors beyond Big-O (extends concept from #7).
48. [Time: 3590s (~59m 50s)] Complexity L48: Evaluate scalability for 10^6+ elements and propose improvements (extends concept from #8).
49. [Time: 3660s (~1h 1m)] Complexity L49: Document trade-offs for real-time or memory-constrained environments (extends concept from #9).
50. [Time: 3730s (~1h 2m 10s)] Complexity L50: Capstone: produce a complexity report for a multi-stage pipeline (extends concept from #10).
51. [Time: 3800s (~1h 3m 20s)] Complexity L51: Derive tight bounds and identify dominant terms (extends concept from #11).
52. [Time: 3870s (~1h 4m 30s)] Complexity L52: Provide best/average/worst-case analysis with example inputs (extends concept from #12).
53. [Time: 3940s (~1h 5m 40s)] Complexity L53: Compare alternative algorithms and justify selection (extends concept from #13).
54. [Time: 4010s (~1h 6m 50s)] Complexity L54: Empirically benchmark and relate results to theoretical complexity (extends concept from #14).
55. [Time: 4080s (~1h 8m)] Complexity L55: Optimize space while maintaining asymptotic time (extends concept from #15).
56. [Time: 4150s (~1h 9m 10s)] Complexity L56: Analyze recursion depth/stack usage and risk of overflow (extends concept from #16).
57. [Time: 4220s (~1h 10m 20s)] Complexity L57: Consider cache/locality and constant factors beyond Big-O (extends concept from #17).
58. [Time: 4290s (~1h 11m 30s)] Complexity L58: Evaluate scalability for 10^6+ elements and propose improvements (extends concept from #18).
59. [Time: 4360s (~1h 12m 40s)] Complexity L59: Document trade-offs for real-time or memory-constrained environments (extends concept from #19).
60. [Time: 4430s (~1h 13m 50s)] Complexity L60: Capstone: produce a complexity report for a multi-stage pipeline (extends concept from #20).
61. [Time: 4500s (~1h 15m)] Complexity L61: Derive tight bounds and identify dominant terms (extends concept from #21).
62. [Time: 4570s (~1h 16m 10s)] Complexity L62: Provide best/average/worst-case analysis with example inputs (extends concept from #22).
63. [Time: 4640s (~1h 17m 20s)] Complexity L63: Compare alternative algorithms and justify selection (extends concept from #23).
64. [Time: 4710s (~1h 18m 30s)] Complexity L64: Empirically benchmark and relate results to theoretical complexity (extends concept from #24).
65. [Time: 4780s (~1h 19m 40s)] Complexity L65: Optimize space while maintaining asymptotic time (extends concept from #25).
66. [Time: 4850s (~1h 20m 50s)] Complexity L66: Analyze recursion depth/stack usage and risk of overflow (extends concept from #26).
67. [Time: 4920s (~1h 22m)] Complexity L67: Consider cache/locality and constant factors beyond Big-O (extends concept from #27).
68. [Time: 4990s (~1h 23m 10s)] Complexity L68: Evaluate scalability for 10^6+ elements and propose improvements (extends concept from #28).
69. [Time: 5060s (~1h 24m 20s)] Complexity L69: Document trade-offs for real-time or memory-constrained environments (extends concept from #29).
70. [Time: 5130s (~1h 25m 30s)] Complexity L70: Capstone: produce a complexity report for a multi-stage pipeline (extends concept from #30).
71. [Time: 5200s (~1h 26m 40s)] Complexity L71: Derive tight bounds and identify dominant terms (extends concept from #31).
72. [Time: 5270s (~1h 27m 50s)] Complexity L72: Provide best/average/worst-case analysis with example inputs (extends concept from #32).
73. [Time: 5340s (~1h 29m)] Complexity L73: Compare alternative algorithms and justify selection (extends concept from #33).
74. [Time: 5410s (~1h 30m 10s)] Complexity L74: Empirically benchmark and relate results to theoretical complexity (extends concept from #34).
75. [Time: 5480s (~1h 31m 20s)] Complexity L75: Optimize space while maintaining asymptotic time (extends concept from #35).
76. [Time: 5550s (~1h 32m 30s)] Complexity L76: Analyze recursion depth/stack usage and risk of overflow (extends concept from #36).
77. [Time: 5620s (~1h 33m 40s)] Complexity L77: Consider cache/locality and constant factors beyond Big-O (extends concept from #37).
78. [Time: 5690s (~1h 34m 50s)] Complexity L78: Evaluate scalability for 10^6+ elements and propose improvements (extends concept from #38).
79. [Time: 5760s (~1h 36m)] Complexity L79: Document trade-offs for real-time or memory-constrained environments (extends concept from #39).
80. [Time: 5830s (~1h 37m 10s)] Complexity L80: Capstone: produce a complexity report for a multi-stage pipeline (extends concept from #40).
81. [Time: 5900s (~1h 38m 20s)] Complexity L81: Derive tight bounds and identify dominant terms (extends concept from #1).
82. [Time: 5970s (~1h 39m 30s)] Complexity L82: Provide best/average/worst-case analysis with example inputs (extends concept from #2).
83. [Time: 6040s (~1h 40m 40s)] Complexity L83: Compare alternative algorithms and justify selection (extends concept from #3).
84. [Time: 6110s (~1h 41m 50s)] Complexity L84: Empirically benchmark and relate results to theoretical complexity (extends concept from #4).
85. [Time: 6180s (~1h 43m)] Complexity L85: Optimize space while maintaining asymptotic time (extends concept from #5).
86. [Time: 6250s (~1h 44m 10s)] Complexity L86: Analyze recursion depth/stack usage and risk of overflow (extends concept from #6).
87. [Time: 6320s (~1h 45m 20s)] Complexity L87: Consider cache/locality and constant factors beyond Big-O (extends concept from #7).
88. [Time: 6390s (~1h 46m 30s)] Complexity L88: Evaluate scalability for 10^6+ elements and propose improvements (extends concept from #8).
89. [Time: 6460s (~1h 47m 40s)] Complexity L89: Document trade-offs for real-time or memory-constrained environments (extends concept from #9).
90. [Time: 6530s (~1h 48m 50s)] Complexity L90: Capstone: produce a complexity report for a multi-stage pipeline (extends concept from #10).
91. [Time: 6600s (~1h 50m)] Complexity L91: Derive tight bounds and identify dominant terms (extends concept from #11).
92. [Time: 6670s (~1h 51m 10s)] Complexity L92: Provide best/average/worst-case analysis with example inputs (extends concept from #12).
93. [Time: 6740s (~1h 52m 20s)] Complexity L93: Compare alternative algorithms and justify selection (extends concept from #13).
94. [Time: 6810s (~1h 53m 30s)] Complexity L94: Empirically benchmark and relate results to theoretical complexity (extends concept from #14).
95. [Time: 6880s (~1h 54m 40s)] Complexity L95: Optimize space while maintaining asymptotic time (extends concept from #15).
96. [Time: 6950s (~1h 55m 50s)] Complexity L96: Analyze recursion depth/stack usage and risk of overflow (extends concept from #16).
97. [Time: 7020s (~1h 57m)] Complexity L97: Consider cache/locality and constant factors beyond Big-O (extends concept from #17).
98. [Time: 7090s (~1h 58m 10s)] Complexity L98: Evaluate scalability for 10^6+ elements and propose improvements (extends concept from #18).
99. [Time: 7160s (~1h 59m 20s)] Complexity L99: Document trade-offs for real-time or memory-constrained environments (extends concept from #19).
100. [Time: 7230s (~2h 0m 30s)] Complexity L100: Capstone: produce a complexity report for a multi-stage pipeline (extends concept from #20).
