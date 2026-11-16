# Algorithm Writing

## Review Workflow
- Problems are listed in increasing difficulty (1-100).
- Solve one problem at a time in this folder (create your own `.c`/notes files as needed).
- When done, add a note/comment: `DONE: <problem number> - awaiting review`.
- I will review your solution. If it is satisfactory and considered a strong answer, proceed to the next problem.
- If not satisfactory, revise the same problem before moving on.
- **Reset policy (requested):** solutions/files in this track may be reset one by one daily to encourage spaced re-practice. Keep backups of work you want to retain.

---

## Problem Statements

1. [Time: 300s (~5m)] Given two integers, write an algorithm to output the maximum, minimum, and whether they are equal.
2. [Time: 370s (~6m 10s)] Write an algorithm to determine if an integer is even, odd, zero, positive, or negative in one pass of decisions.
3. [Time: 440s (~7m 20s)] Write an algorithm to swap two variables using a temporary variable and explain the state at each step.
4. [Time: 510s (~8m 30s)] Write an algorithm to swap two numeric variables without using a temporary variable; list preconditions.
5. [Time: 580s (~9m 40s)] Compute the sum of the first N natural numbers and verify it against the formula N*(N+1)/2.
6. [Time: 650s (~10m 50s)] Write an algorithm to find the largest and second largest among three distinct numbers.
7. [Time: 720s (~12m)] Convert a temperature from Celsius to Fahrenheit and Kelvin; define rounding behavior.
8. [Time: 790s (~13m 10s)] Determine whether a given year is a leap year using the Gregorian rules.
9. [Time: 860s (~14m 20s)] Compute simple interest and total amount given principal, rate, and time with input validation.
10. [Time: 930s (~15m 30s)] Calculate area and perimeter of a rectangle and detect invalid (non-positive) dimensions.
11. [Time: 1000s (~16m 40s)] Reverse a given integer while preserving its sign; define behavior for trailing zeros.
12. [Time: 1070s (~17m 50s)] Check if an integer is a palindrome without converting it to a string.
13. [Time: 1140s (~19m)] Compute factorial of N iteratively and state the largest N safe for 32-bit int.
14. [Time: 1210s (~20m 10s)] Generate the first N Fibonacci numbers iteratively with clear initialization steps.
15. [Time: 1280s (~21m 20s)] Determine whether a number is prime using trial division up to sqrt(n).
16. [Time: 1350s (~22m 30s)] Find GCD of two integers using Euclid's algorithm.
17. [Time: 1420s (~23m 40s)] Find LCM of two integers using the relation with GCD; handle zero cases.
18. [Time: 1490s (~24m 50s)] Count digits, sum digits, and compute product of digits for an integer.
19. [Time: 1560s (~26m)] Find all factors of a positive integer and classify it as perfect, abundant, or deficient.
20. [Time: 1630s (~27m 10s)] Convert a non-negative integer from decimal to binary (algorithmic steps, no built-in conversion).
21. [Time: 1700s (~28m 20s)] Compute power(x, n) for integer n >= 0 using repeated multiplication.
22. [Time: 1770s (~29m 30s)] Compute power(x, n) using fast exponentiation (exponentiation by squaring).
23. [Time: 1840s (~30m 40s)] Check whether a number is an Armstrong/narcissistic number for its digit length.
24. [Time: 1910s (~31m 50s)] Determine if a string is a palindrome considering only alphanumeric characters (algorithm description).
25. [Time: 1980s (~33m)] Find the maximum element in a list/array of N integers.
26. [Time: 2050s (~34m 10s)] Compute the average of N numbers and also report how many are above average.
27. [Time: 2120s (~35m 20s)] Search for a key in an unsorted array using linear search and return its index or -1.
28. [Time: 2190s (~36m 30s)] Search for a key in a sorted array using binary search (iterative).
29. [Time: 2260s (~37m 40s)] Sort an array of N integers using bubble sort; count swaps.
30. [Time: 2330s (~38m 50s)] Sort an array using selection sort; count comparisons.
31. [Time: 2400s (~40m)] Sort an array using insertion sort and show invariants after each pass (conceptually).
32. [Time: 2470s (~41m 10s)] Merge two sorted arrays into one sorted array.
33. [Time: 2540s (~42m 20s)] Remove duplicate elements from a sorted array in-place (algorithm).
34. [Time: 2610s (~43m 30s)] Rotate an array right by K positions with O(1) extra space.
35. [Time: 2680s (~44m 40s)] Find the missing number in an array containing 1..N with one missing.
36. [Time: 2750s (~45m 50s)] Find the single non-repeating element when all others appear twice (XOR-based algorithm).
37. [Time: 2820s (~47m)] Check if two strings are anagrams using frequency counting.
38. [Time: 2890s (~48m 10s)] Find the first non-repeating character in a string.
39. [Time: 2960s (~49m 20s)] Reverse words in a sentence while preserving single spaces (algorithm).
40. [Time: 3030s (~50m 30s)] Run-length encode a string (e.g., aaabb -> a3b2).
41. [Time: 3100s (~51m 40s)] Validate balanced parentheses for (), {}, [] in an expression using a stack idea.
42. [Time: 3170s (~52m 50s)] Evaluate a postfix expression using a stack (algorithm).
43. [Time: 3240s (~54m)] Implement queue operations (enqueue, dequeue) conceptually using a circular array.
44. [Time: 3310s (~55m 10s)] Design an algorithm to find the kth smallest element in an unsorted array (selection idea).
45. [Time: 3380s (~56m 20s)] Compute prefix sums array and answer range-sum queries.
46. [Time: 3450s (~57m 30s)] Find subarray with maximum sum (Kadane's algorithm) and return indices.
47. [Time: 3520s (~58m 40s)] Detect if a linked list has a cycle using Floyd's tortoise and hare (algorithm).
48. [Time: 3590s (~59m 50s)] Reverse a singly linked list iteratively (pointer steps).
49. [Time: 3660s (~1h 1m)] Find middle node of a singly linked list in one pass.
50. [Time: 3730s (~1h 2m 10s)] Merge two sorted linked lists into one sorted list.
51. [Time: 3800s (~1h 3m 20s)] Check if a binary tree is height-balanced (algorithm).
52. [Time: 3870s (~1h 4m 30s)] Compute height and number of nodes in a binary tree.
53. [Time: 3940s (~1h 5m 40s)] Perform inorder, preorder, and postorder traversals (recursive) and state visit order.
54. [Time: 4010s (~1h 6m 50s)] Level-order traversal of a binary tree using a queue.
55. [Time: 4080s (~1h 8m)] Check if two binary trees are identical.
56. [Time: 4150s (~1h 9m 10s)] Insert and search in a binary search tree (BST).
57. [Time: 4220s (~1h 10m 20s)] Find lowest common ancestor in a BST.
58. [Time: 4290s (~1h 11m 30s)] Represent a graph using adjacency list and adjacency matrix; compare space.
59. [Time: 4360s (~1h 12m 40s)] Perform BFS from a source node in an unweighted graph.
60. [Time: 4430s (~1h 13m 50s)] Perform DFS (recursive and iterative) and classify edges conceptually.
61. [Time: 4500s (~1h 15m)] Detect a cycle in an undirected graph using DFS/Union-Find (choose and describe).
62. [Time: 4570s (~1h 16m 10s)] Detect a cycle in a directed graph using DFS colors/recursion stack.
63. [Time: 4640s (~1h 17m 20s)] Topological sort of a DAG using Kahn's algorithm or DFS.
64. [Time: 4710s (~1h 18m 30s)] Find shortest path in an unweighted graph using BFS.
65. [Time: 4780s (~1h 19m 40s)] Dijkstra's algorithm for shortest paths in weighted graph with non-negative weights.
66. [Time: 4850s (~1h 20m 50s)] Compute minimum spanning tree using Kruskal's or Prim's algorithm.
67. [Time: 4920s (~1h 22m)] 0/1 Knapsack problem: write DP algorithm and define state transition.
68. [Time: 4990s (~1h 23m 10s)] Longest common subsequence (LCS) of two strings: DP formulation.
69. [Time: 5060s (~1h 24m 20s)] Edit distance between two strings: DP formulation.
70. [Time: 5130s (~1h 25m 30s)] Coin change (minimum coins) problem: DP algorithm.
71. [Time: 5200s (~1h 26m 40s)] Activity selection problem: greedy algorithm and proof idea.
72. [Time: 5270s (~1h 27m 50s)] Fractional knapsack: greedy strategy and why it works.
73. [Time: 5340s (~1h 29m)] Find majority element (> n/2 times) using Boyer-Moore voting algorithm.
74. [Time: 5410s (~1h 30m 10s)] Count inversions in an array using modified merge sort.
75. [Time: 5480s (~1h 31m 20s)] Find median of two sorted arrays of same size (algorithmic approach).
76. [Time: 5550s (~1h 32m 30s)] Implement binary search on answer: find minimum capacity to ship packages in D days (outline).
77. [Time: 5620s (~1h 33m 40s)] Sliding window maximum in an array of size N with window K.
78. [Time: 5690s (~1h 34m 50s)] Longest substring without repeating characters using sliding window.
79. [Time: 5760s (~1h 36m)] Design LRU cache operations (get/put) with O(1) average using hash map + doubly linked list.
80. [Time: 5830s (~1h 37m 10s)] Serialize and deserialize a binary tree (define format and algorithm).
81. [Time: 5900s (~1h 38m 20s)] Trie insert/search for a set of lowercase strings.
82. [Time: 5970s (~1h 39m 30s)] Word break problem: can a string be segmented into dictionary words (DP).
83. [Time: 6040s (~1h 40m 40s)] Find number of islands in a binary grid using BFS/DFS.
84. [Time: 6110s (~1h 41m 50s)] Rotting oranges / multi-source BFS minimum time problem.
85. [Time: 6180s (~1h 43m)] N-Queens: backtracking algorithm to place N queens safely.
86. [Time: 6250s (~1h 44m 10s)] Generate all permutations of a string/array using backtracking.
87. [Time: 6320s (~1h 45m 20s)] Sudoku solver outline using backtracking with constraint checks.
88. [Time: 6390s (~1h 46m 30s)] Compute convex hull of 2D points using Graham scan or Andrew's monotone chain.
89. [Time: 6460s (~1h 47m 40s)] Closest pair of points in 2D using divide and conquer (high-level algorithm).
90. [Time: 6530s (~1h 48m 50s)] KMP string matching: build LPS array and search pattern.
91. [Time: 6600s (~1h 50m)] Rabin-Karp rolling hash for substring search and collision handling idea.
92. [Time: 6670s (~1h 51m 10s)] Union-Find (Disjoint Set Union) with path compression and union by rank.
93. [Time: 6740s (~1h 52m 20s)] Design a rate limiter algorithm (token bucket or leaky bucket).
94. [Time: 6810s (~1h 53m 30s)] Find strongly connected components in a directed graph (Kosaraju/Tarjan).
95. [Time: 6880s (~1h 54m 40s)] Compute bridges and articulation points in an undirected graph (Tarjan).
96. [Time: 6950s (~1h 55m 50s)] Shortest path with negative edges using Bellman-Ford and detect negative cycles.
97. [Time: 7020s (~1h 57m)] All-pairs shortest paths using Floyd-Warshall; state complexity.
98. [Time: 7090s (~1h 58m 10s)] A* search algorithm: heuristic design and admissibility considerations.
99. [Time: 7160s (~1h 59m 20s)] Design an external merge sort algorithm for data larger than memory.
100. [Time: 7230s (~2h 0m 30s)] Write an algorithm for consistent hashing and node add/remove behavior.
