# Arrays and Strings

## Review Workflow
- Problems are listed in increasing difficulty (1-100).
- Solve one problem at a time in this folder (create your own `.c`/notes files as needed).
- When done, add a note/comment: `DONE: <problem number> - awaiting review`.
- I will review your solution. If it is satisfactory and considered a strong answer, proceed to the next problem.
- If not satisfactory, revise the same problem before moving on.
- **Reset policy (requested):** solutions/files in this track may be reset one by one daily to encourage spaced re-practice. Keep backups of work you want to retain.

---

## Problem Statements

1. [Time: 300s (~5m)] Input N integers into an array and print them in reverse order.
2. [Time: 370s (~6m 10s)] Find min, max, sum, and average of array elements.
3. [Time: 440s (~7m 20s)] Copy one array to another and verify equality.
4. [Time: 510s (~8m 30s)] Linear search: find first and last index of a key.
5. [Time: 580s (~9m 40s)] Count occurrences of each value in a small-range integer array.
6. [Time: 650s (~10m 50s)] Insert an element at a given position in an array (shifting).
7. [Time: 720s (~12m)] Delete an element at a given position in an array.
8. [Time: 790s (~13m 10s)] Remove duplicates from an unsorted array.
9. [Time: 860s (~14m 20s)] Rotate array left/right by K positions.
10. [Time: 930s (~15m 30s)] Merge two arrays and sort the result.
11. [Time: 1000s (~16m 40s)] Find second largest element without sorting.
12. [Time: 1070s (~17m 50s)] Move all zeros to end while maintaining order of non-zeros.
13. [Time: 1140s (~19m)] Reverse an array in-place using two pointers.
14. [Time: 1210s (~20m 10s)] Compute prefix sums and answer range sum queries.
15. [Time: 1280s (~21m 20s)] Find pair with given sum in a sorted array (two pointers).
16. [Time: 1350s (~22m 30s)] Implement string length, copy, compare without standard library functions.
17. [Time: 1420s (~23m 40s)] Concatenate two strings safely into a buffer.
18. [Time: 1490s (~24m 50s)] Check if a string is palindrome (case-insensitive).
19. [Time: 1560s (~26m)] Count vowels, consonants, digits, spaces in a string.
20. [Time: 1630s (~27m 10s)] Reverse words in a sentence.
21. [Time: 1700s (~28m 20s)] Remove leading/trailing/multiple intermediate spaces from a string.
22. [Time: 1770s (~29m 30s)] Find first non-repeating character in a string.
23. [Time: 1840s (~30m 40s)] Check if two strings are anagrams.
24. [Time: 1910s (~31m 50s)] Implement substring search (naive).
25. [Time: 1980s (~33m)] Convert string to integer (`atoi`-like) with overflow/sign handling.
26. [Time: 2050s (~34m 10s)] Convert integer to string for any base (2-16).
27. [Time: 2120s (~35m 20s)] Tokenize a string by delimiters (custom `strtok`-like behavior).
28. [Time: 2190s (~36m 30s)] Implement dynamic array growth strategy (manual realloc).
29. [Time: 2260s (~37m 40s)] 2D array/matrix addition and multiplication.
30. [Time: 2330s (~38m 50s)] Transpose a matrix in-place for square matrix and out-of-place for rectangular.
31. [Time: 2400s (~40m)] Spiral order traversal of a matrix.
32. [Time: 2470s (~41m 10s)] Search in a row-wise and column-wise sorted matrix.
33. [Time: 2540s (~42m 20s)] Find longest common prefix among array of strings.
34. [Time: 2610s (~43m 30s)] Run-length compress/decompress a string.
35. [Time: 2680s (~44m 40s)] Check if one string is rotation of another.
36. [Time: 2750s (~45m 50s)] Implement a simple text justification or wrap for fixed width.
37. [Time: 2820s (~47m)] Store and sort array of strings (names) lexicographically.
38. [Time: 2890s (~48m 10s)] Find all permutations of characters in a string (small n).
39. [Time: 2960s (~49m 20s)] Implement Rabin-Karp or KMP for pattern matching in strings.
40. [Time: 3030s (~50m 30s)] Build a simple line editor buffer supporting insert/delete operations on char array.
41. [Time: 3100s (~51m 40s)] Arrays & Strings L41: add bounds checking and buffer-overflow prevention — apply to/refine problem #1 with a clear correctness criterion.
42. [Time: 3170s (~52m 50s)] Arrays & Strings L42: handle Unicode/locale considerations conceptually where relevant — apply to/refine problem #2 with a clear correctness criterion.
43. [Time: 3240s (~54m)] Arrays & Strings L43: use dynamic memory safely for variable-size inputs — apply to/refine problem #3 with a clear correctness criterion.
44. [Time: 3310s (~55m 10s)] Arrays & Strings L44: optimize from O(n^2) to O(n)/O(n log n) where possible — apply to/refine problem #4 with a clear correctness criterion.
45. [Time: 3380s (~56m 20s)] Arrays & Strings L45: support in-place operations with minimal extra space — apply to/refine problem #5 with a clear correctness criterion.
46. [Time: 3450s (~57m 30s)] Arrays & Strings L46: write reusable functions with clear ownership of memory — apply to/refine problem #6 with a clear correctness criterion.
47. [Time: 3520s (~58m 40s)] Arrays & Strings L47: add fuzz/edge-case tests (empty, single element, all same) — apply to/refine problem #7 with a clear correctness criterion.
48. [Time: 3590s (~59m 50s)] Arrays & Strings L48: compare static vs dynamic array/string approaches — apply to/refine problem #8 with a clear correctness criterion.
49. [Time: 3660s (~1h 1m)] Arrays & Strings L49: handle very large inputs efficiently — apply to/refine problem #9 with a clear correctness criterion.
50. [Time: 3730s (~1h 2m 10s)] Arrays & Strings L50: build a capstone text/array processing mini-tool — apply to/refine problem #10 with a clear correctness criterion.
51. [Time: 3800s (~1h 3m 20s)] Arrays & Strings L51: add bounds checking and buffer-overflow prevention — apply to/refine problem #11 with a clear correctness criterion.
52. [Time: 3870s (~1h 4m 30s)] Arrays & Strings L52: handle Unicode/locale considerations conceptually where relevant — apply to/refine problem #12 with a clear correctness criterion.
53. [Time: 3940s (~1h 5m 40s)] Arrays & Strings L53: use dynamic memory safely for variable-size inputs — apply to/refine problem #13 with a clear correctness criterion.
54. [Time: 4010s (~1h 6m 50s)] Arrays & Strings L54: optimize from O(n^2) to O(n)/O(n log n) where possible — apply to/refine problem #14 with a clear correctness criterion.
55. [Time: 4080s (~1h 8m)] Arrays & Strings L55: support in-place operations with minimal extra space — apply to/refine problem #15 with a clear correctness criterion.
56. [Time: 4150s (~1h 9m 10s)] Arrays & Strings L56: write reusable functions with clear ownership of memory — apply to/refine problem #16 with a clear correctness criterion.
57. [Time: 4220s (~1h 10m 20s)] Arrays & Strings L57: add fuzz/edge-case tests (empty, single element, all same) — apply to/refine problem #17 with a clear correctness criterion.
58. [Time: 4290s (~1h 11m 30s)] Arrays & Strings L58: compare static vs dynamic array/string approaches — apply to/refine problem #18 with a clear correctness criterion.
59. [Time: 4360s (~1h 12m 40s)] Arrays & Strings L59: handle very large inputs efficiently — apply to/refine problem #19 with a clear correctness criterion.
60. [Time: 4430s (~1h 13m 50s)] Arrays & Strings L60: build a capstone text/array processing mini-tool — apply to/refine problem #20 with a clear correctness criterion.
61. [Time: 4500s (~1h 15m)] Arrays & Strings L61: add bounds checking and buffer-overflow prevention — apply to/refine problem #21 with a clear correctness criterion.
62. [Time: 4570s (~1h 16m 10s)] Arrays & Strings L62: handle Unicode/locale considerations conceptually where relevant — apply to/refine problem #22 with a clear correctness criterion.
63. [Time: 4640s (~1h 17m 20s)] Arrays & Strings L63: use dynamic memory safely for variable-size inputs — apply to/refine problem #23 with a clear correctness criterion.
64. [Time: 4710s (~1h 18m 30s)] Arrays & Strings L64: optimize from O(n^2) to O(n)/O(n log n) where possible — apply to/refine problem #24 with a clear correctness criterion.
65. [Time: 4780s (~1h 19m 40s)] Arrays & Strings L65: support in-place operations with minimal extra space — apply to/refine problem #25 with a clear correctness criterion.
66. [Time: 4850s (~1h 20m 50s)] Arrays & Strings L66: write reusable functions with clear ownership of memory — apply to/refine problem #26 with a clear correctness criterion.
67. [Time: 4920s (~1h 22m)] Arrays & Strings L67: add fuzz/edge-case tests (empty, single element, all same) — apply to/refine problem #27 with a clear correctness criterion.
68. [Time: 4990s (~1h 23m 10s)] Arrays & Strings L68: compare static vs dynamic array/string approaches — apply to/refine problem #28 with a clear correctness criterion.
69. [Time: 5060s (~1h 24m 20s)] Arrays & Strings L69: handle very large inputs efficiently — apply to/refine problem #29 with a clear correctness criterion.
70. [Time: 5130s (~1h 25m 30s)] Arrays & Strings L70: build a capstone text/array processing mini-tool — apply to/refine problem #30 with a clear correctness criterion.
71. [Time: 5200s (~1h 26m 40s)] Arrays & Strings L71: add bounds checking and buffer-overflow prevention — apply to/refine problem #31 with a clear correctness criterion.
72. [Time: 5270s (~1h 27m 50s)] Arrays & Strings L72: handle Unicode/locale considerations conceptually where relevant — apply to/refine problem #32 with a clear correctness criterion.
73. [Time: 5340s (~1h 29m)] Arrays & Strings L73: use dynamic memory safely for variable-size inputs — apply to/refine problem #33 with a clear correctness criterion.
74. [Time: 5410s (~1h 30m 10s)] Arrays & Strings L74: optimize from O(n^2) to O(n)/O(n log n) where possible — apply to/refine problem #34 with a clear correctness criterion.
75. [Time: 5480s (~1h 31m 20s)] Arrays & Strings L75: support in-place operations with minimal extra space — apply to/refine problem #35 with a clear correctness criterion.
76. [Time: 5550s (~1h 32m 30s)] Arrays & Strings L76: write reusable functions with clear ownership of memory — apply to/refine problem #36 with a clear correctness criterion.
77. [Time: 5620s (~1h 33m 40s)] Arrays & Strings L77: add fuzz/edge-case tests (empty, single element, all same) — apply to/refine problem #37 with a clear correctness criterion.
78. [Time: 5690s (~1h 34m 50s)] Arrays & Strings L78: compare static vs dynamic array/string approaches — apply to/refine problem #38 with a clear correctness criterion.
79. [Time: 5760s (~1h 36m)] Arrays & Strings L79: handle very large inputs efficiently — apply to/refine problem #39 with a clear correctness criterion.
80. [Time: 5830s (~1h 37m 10s)] Arrays & Strings L80: build a capstone text/array processing mini-tool — apply to/refine problem #40 with a clear correctness criterion.
81. [Time: 5900s (~1h 38m 20s)] Arrays & Strings L81: add bounds checking and buffer-overflow prevention — apply to/refine problem #1 with a clear correctness criterion.
82. [Time: 5970s (~1h 39m 30s)] Arrays & Strings L82: handle Unicode/locale considerations conceptually where relevant — apply to/refine problem #2 with a clear correctness criterion.
83. [Time: 6040s (~1h 40m 40s)] Arrays & Strings L83: use dynamic memory safely for variable-size inputs — apply to/refine problem #3 with a clear correctness criterion.
84. [Time: 6110s (~1h 41m 50s)] Arrays & Strings L84: optimize from O(n^2) to O(n)/O(n log n) where possible — apply to/refine problem #4 with a clear correctness criterion.
85. [Time: 6180s (~1h 43m)] Arrays & Strings L85: support in-place operations with minimal extra space — apply to/refine problem #5 with a clear correctness criterion.
86. [Time: 6250s (~1h 44m 10s)] Arrays & Strings L86: write reusable functions with clear ownership of memory — apply to/refine problem #6 with a clear correctness criterion.
87. [Time: 6320s (~1h 45m 20s)] Arrays & Strings L87: add fuzz/edge-case tests (empty, single element, all same) — apply to/refine problem #7 with a clear correctness criterion.
88. [Time: 6390s (~1h 46m 30s)] Arrays & Strings L88: compare static vs dynamic array/string approaches — apply to/refine problem #8 with a clear correctness criterion.
89. [Time: 6460s (~1h 47m 40s)] Arrays & Strings L89: handle very large inputs efficiently — apply to/refine problem #9 with a clear correctness criterion.
90. [Time: 6530s (~1h 48m 50s)] Arrays & Strings L90: build a capstone text/array processing mini-tool — apply to/refine problem #10 with a clear correctness criterion.
91. [Time: 6600s (~1h 50m)] Arrays & Strings L91: add bounds checking and buffer-overflow prevention — apply to/refine problem #11 with a clear correctness criterion.
92. [Time: 6670s (~1h 51m 10s)] Arrays & Strings L92: handle Unicode/locale considerations conceptually where relevant — apply to/refine problem #12 with a clear correctness criterion.
93. [Time: 6740s (~1h 52m 20s)] Arrays & Strings L93: use dynamic memory safely for variable-size inputs — apply to/refine problem #13 with a clear correctness criterion.
94. [Time: 6810s (~1h 53m 30s)] Arrays & Strings L94: optimize from O(n^2) to O(n)/O(n log n) where possible — apply to/refine problem #14 with a clear correctness criterion.
95. [Time: 6880s (~1h 54m 40s)] Arrays & Strings L95: support in-place operations with minimal extra space — apply to/refine problem #15 with a clear correctness criterion.
96. [Time: 6950s (~1h 55m 50s)] Arrays & Strings L96: write reusable functions with clear ownership of memory — apply to/refine problem #16 with a clear correctness criterion.
97. [Time: 7020s (~1h 57m)] Arrays & Strings L97: add fuzz/edge-case tests (empty, single element, all same) — apply to/refine problem #17 with a clear correctness criterion.
98. [Time: 7090s (~1h 58m 10s)] Arrays & Strings L98: compare static vs dynamic array/string approaches — apply to/refine problem #18 with a clear correctness criterion.
99. [Time: 7160s (~1h 59m 20s)] Arrays & Strings L99: handle very large inputs efficiently — apply to/refine problem #19 with a clear correctness criterion.
100. [Time: 7230s (~2h 0m 30s)] Arrays & Strings L100: build a capstone text/array processing mini-tool — apply to/refine problem #20 with a clear correctness criterion.
