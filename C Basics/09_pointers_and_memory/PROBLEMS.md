# Pointers and Memory

## Review Workflow
- Problems are listed in increasing difficulty (1-100).
- Solve one problem at a time in this folder (create your own `.c`/notes files as needed).
- When done, add a note/comment: `DONE: <problem number> - awaiting review`.
- I will review your solution. If it is satisfactory and considered a strong answer, proceed to the next problem.
- If not satisfactory, revise the same problem before moving on.
- **Reset policy (requested):** solutions/files in this track may be reset one by one daily to encourage spaced re-practice. Keep backups of work you want to retain.

---

## Problem Statements

1. [Time: 300s (~5m)] Print address and value of variables using pointers.
2. [Time: 370s (~6m 10s)] Demonstrate pointer arithmetic across an int array.
3. [Time: 440s (~7m 20s)] Use pointer to modify a variable inside a function.
4. [Time: 510s (~8m 30s)] Swap two values using pointers.
5. [Time: 580s (~9m 40s)] Traverse array using pointer notation instead of indexing.
6. [Time: 650s (~10m 50s)] Pass array to function and compute sum via pointer.
7. [Time: 720s (~12m)] Use pointer to char to iterate over a string.
8. [Time: 790s (~13m 10s)] Dynamic allocation of single int with `malloc` and proper `free`.
9. [Time: 860s (~14m 20s)] Dynamic array allocation with `malloc`/`calloc`; initialize and print.
10. [Time: 930s (~15m 30s)] Resize dynamic array with `realloc` safely (handle failure).
11. [Time: 1000s (~16m 40s)] Allocate 2D array dynamically (array of pointers) and free correctly.
12. [Time: 1070s (~17m 50s)] Allocate contiguous 2D array dynamically and index it.
13. [Time: 1140s (~19m)] Return dynamically allocated string from a function; caller frees.
14. [Time: 1210s (~20m 10s)] Demonstrate NULL pointer checks and defensive programming.
15. [Time: 1280s (~21m 20s)] Show dangling pointer scenario and correct fix.
16. [Time: 1350s (~22m 30s)] Show memory leak scenario and fix with proper ownership.
17. [Time: 1420s (~23m 40s)] Use `memset`, `memcpy`, `memmove` correctly on buffers.
18. [Time: 1490s (~24m 50s)] Demonstrate difference between shallow and deep copy for structs with pointers.
19. [Time: 1560s (~26m)] Implement dynamic string append (like simple string builder).
20. [Time: 1630s (~27m 10s)] Function pointer basics: call different operations via function pointer.
21. [Time: 1700s (~28m 20s)] Array of function pointers for a command/menu dispatch table.
22. [Time: 1770s (~29m 30s)] Pointer to pointer: modify a pointer in caller (e.g., allocate in function).
23. [Time: 1840s (~30m 40s)] Const correctness with pointers (`const int*`, `int* const`, etc.).
24. [Time: 1910s (~31m 50s)] Implement a simple singly linked list node create/insert/free.
25. [Time: 1980s (~33m)] Detect and avoid double free in a small example.
26. [Time: 2050s (~34m 10s)] Use `valgrind`/ASan concepts: identify invalid read/write in sample code.
27. [Time: 2120s (~35m 20s)] Implement ownership transfer conventions in API design (comments/docs).
28. [Time: 2190s (~36m 30s)] Aligning buffers and understanding pointer casts safely.
29. [Time: 2260s (~37m 40s)] Implement a generic swap using `void*` and byte size.
30. [Time: 2330s (~38m 50s)] Create a simple memory pool/arena allocator for fixed-size blocks.
31. [Time: 2400s (~40m)] Reference counting basics for shared dynamically allocated object.
32. [Time: 2470s (~41m 10s)] Implement dynamic stack (push/pop) using pointers and realloc growth.
33. [Time: 2540s (~42m 20s)] Parse command-line args into dynamically allocated structures.
34. [Time: 2610s (~43m 30s)] Serialize pointer-based structure carefully (no raw pointers) to a buffer/file.
35. [Time: 2680s (~44m 40s)] Implement safe string duplication (`strdup`-like) and error handling.
36. [Time: 2750s (~45m 50s)] Use flexible array member in struct with dynamic allocation.
37. [Time: 2820s (~47m)] Demonstrate pointer aliasing and `restrict` keyword usage.
38. [Time: 2890s (~48m 10s)] Build a simple observer/callback registration using function pointers.
39. [Time: 2960s (~49m 20s)] Implement shallow vs deep free for nested pointer structures.
40. [Time: 3030s (~50m 30s)] Capstone: implement a small dynamic container (vector/list/map-lite) with clear memory ownership rules.
41. [Time: 3100s (~51m 40s)] Pointers & Memory L41: add rigorous NULL/allocation-failure handling — apply to/refine problem #1 with a clear correctness criterion.
42. [Time: 3170s (~52m 50s)] Pointers & Memory L42: eliminate leaks and use-after-free with clear ownership — apply to/refine problem #2 with a clear correctness criterion.
43. [Time: 3240s (~54m)] Pointers & Memory L43: support deep copy and proper destructor/free routines — apply to/refine problem #3 with a clear correctness criterion.
44. [Time: 3310s (~55m 10s)] Pointers & Memory L44: make APIs const-correct and self-documenting — apply to/refine problem #4 with a clear correctness criterion.
45. [Time: 3380s (~56m 20s)] Pointers & Memory L45: handle alignment and strict aliasing safely — apply to/refine problem #5 with a clear correctness criterion.
46. [Time: 3450s (~57m 30s)] Pointers & Memory L46: instrument allocations/frees to detect mismatches — apply to/refine problem #6 with a clear correctness criterion.
47. [Time: 3520s (~58m 40s)] Pointers & Memory L47: generalize with `void*` while preserving type safety patterns — apply to/refine problem #7 with a clear correctness criterion.
48. [Time: 3590s (~59m 50s)] Pointers & Memory L48: stress-test with edge sizes (0, 1, large) and realloc paths — apply to/refine problem #8 with a clear correctness criterion.
49. [Time: 3660s (~1h 1m)] Pointers & Memory L49: compare stack vs heap allocation trade-offs — apply to/refine problem #9 with a clear correctness criterion.
50. [Time: 3730s (~1h 2m 10s)] Pointers & Memory L50: build a capstone allocator/container with verified correctness — apply to/refine problem #10 with a clear correctness criterion.
51. [Time: 3800s (~1h 3m 20s)] Pointers & Memory L51: add rigorous NULL/allocation-failure handling — apply to/refine problem #11 with a clear correctness criterion.
52. [Time: 3870s (~1h 4m 30s)] Pointers & Memory L52: eliminate leaks and use-after-free with clear ownership — apply to/refine problem #12 with a clear correctness criterion.
53. [Time: 3940s (~1h 5m 40s)] Pointers & Memory L53: support deep copy and proper destructor/free routines — apply to/refine problem #13 with a clear correctness criterion.
54. [Time: 4010s (~1h 6m 50s)] Pointers & Memory L54: make APIs const-correct and self-documenting — apply to/refine problem #14 with a clear correctness criterion.
55. [Time: 4080s (~1h 8m)] Pointers & Memory L55: handle alignment and strict aliasing safely — apply to/refine problem #15 with a clear correctness criterion.
56. [Time: 4150s (~1h 9m 10s)] Pointers & Memory L56: instrument allocations/frees to detect mismatches — apply to/refine problem #16 with a clear correctness criterion.
57. [Time: 4220s (~1h 10m 20s)] Pointers & Memory L57: generalize with `void*` while preserving type safety patterns — apply to/refine problem #17 with a clear correctness criterion.
58. [Time: 4290s (~1h 11m 30s)] Pointers & Memory L58: stress-test with edge sizes (0, 1, large) and realloc paths — apply to/refine problem #18 with a clear correctness criterion.
59. [Time: 4360s (~1h 12m 40s)] Pointers & Memory L59: compare stack vs heap allocation trade-offs — apply to/refine problem #19 with a clear correctness criterion.
60. [Time: 4430s (~1h 13m 50s)] Pointers & Memory L60: build a capstone allocator/container with verified correctness — apply to/refine problem #20 with a clear correctness criterion.
61. [Time: 4500s (~1h 15m)] Pointers & Memory L61: add rigorous NULL/allocation-failure handling — apply to/refine problem #21 with a clear correctness criterion.
62. [Time: 4570s (~1h 16m 10s)] Pointers & Memory L62: eliminate leaks and use-after-free with clear ownership — apply to/refine problem #22 with a clear correctness criterion.
63. [Time: 4640s (~1h 17m 20s)] Pointers & Memory L63: support deep copy and proper destructor/free routines — apply to/refine problem #23 with a clear correctness criterion.
64. [Time: 4710s (~1h 18m 30s)] Pointers & Memory L64: make APIs const-correct and self-documenting — apply to/refine problem #24 with a clear correctness criterion.
65. [Time: 4780s (~1h 19m 40s)] Pointers & Memory L65: handle alignment and strict aliasing safely — apply to/refine problem #25 with a clear correctness criterion.
66. [Time: 4850s (~1h 20m 50s)] Pointers & Memory L66: instrument allocations/frees to detect mismatches — apply to/refine problem #26 with a clear correctness criterion.
67. [Time: 4920s (~1h 22m)] Pointers & Memory L67: generalize with `void*` while preserving type safety patterns — apply to/refine problem #27 with a clear correctness criterion.
68. [Time: 4990s (~1h 23m 10s)] Pointers & Memory L68: stress-test with edge sizes (0, 1, large) and realloc paths — apply to/refine problem #28 with a clear correctness criterion.
69. [Time: 5060s (~1h 24m 20s)] Pointers & Memory L69: compare stack vs heap allocation trade-offs — apply to/refine problem #29 with a clear correctness criterion.
70. [Time: 5130s (~1h 25m 30s)] Pointers & Memory L70: build a capstone allocator/container with verified correctness — apply to/refine problem #30 with a clear correctness criterion.
71. [Time: 5200s (~1h 26m 40s)] Pointers & Memory L71: add rigorous NULL/allocation-failure handling — apply to/refine problem #31 with a clear correctness criterion.
72. [Time: 5270s (~1h 27m 50s)] Pointers & Memory L72: eliminate leaks and use-after-free with clear ownership — apply to/refine problem #32 with a clear correctness criterion.
73. [Time: 5340s (~1h 29m)] Pointers & Memory L73: support deep copy and proper destructor/free routines — apply to/refine problem #33 with a clear correctness criterion.
74. [Time: 5410s (~1h 30m 10s)] Pointers & Memory L74: make APIs const-correct and self-documenting — apply to/refine problem #34 with a clear correctness criterion.
75. [Time: 5480s (~1h 31m 20s)] Pointers & Memory L75: handle alignment and strict aliasing safely — apply to/refine problem #35 with a clear correctness criterion.
76. [Time: 5550s (~1h 32m 30s)] Pointers & Memory L76: instrument allocations/frees to detect mismatches — apply to/refine problem #36 with a clear correctness criterion.
77. [Time: 5620s (~1h 33m 40s)] Pointers & Memory L77: generalize with `void*` while preserving type safety patterns — apply to/refine problem #37 with a clear correctness criterion.
78. [Time: 5690s (~1h 34m 50s)] Pointers & Memory L78: stress-test with edge sizes (0, 1, large) and realloc paths — apply to/refine problem #38 with a clear correctness criterion.
79. [Time: 5760s (~1h 36m)] Pointers & Memory L79: compare stack vs heap allocation trade-offs — apply to/refine problem #39 with a clear correctness criterion.
80. [Time: 5830s (~1h 37m 10s)] Pointers & Memory L80: build a capstone allocator/container with verified correctness — apply to/refine problem #40 with a clear correctness criterion.
81. [Time: 5900s (~1h 38m 20s)] Pointers & Memory L81: add rigorous NULL/allocation-failure handling — apply to/refine problem #1 with a clear correctness criterion.
82. [Time: 5970s (~1h 39m 30s)] Pointers & Memory L82: eliminate leaks and use-after-free with clear ownership — apply to/refine problem #2 with a clear correctness criterion.
83. [Time: 6040s (~1h 40m 40s)] Pointers & Memory L83: support deep copy and proper destructor/free routines — apply to/refine problem #3 with a clear correctness criterion.
84. [Time: 6110s (~1h 41m 50s)] Pointers & Memory L84: make APIs const-correct and self-documenting — apply to/refine problem #4 with a clear correctness criterion.
85. [Time: 6180s (~1h 43m)] Pointers & Memory L85: handle alignment and strict aliasing safely — apply to/refine problem #5 with a clear correctness criterion.
86. [Time: 6250s (~1h 44m 10s)] Pointers & Memory L86: instrument allocations/frees to detect mismatches — apply to/refine problem #6 with a clear correctness criterion.
87. [Time: 6320s (~1h 45m 20s)] Pointers & Memory L87: generalize with `void*` while preserving type safety patterns — apply to/refine problem #7 with a clear correctness criterion.
88. [Time: 6390s (~1h 46m 30s)] Pointers & Memory L88: stress-test with edge sizes (0, 1, large) and realloc paths — apply to/refine problem #8 with a clear correctness criterion.
89. [Time: 6460s (~1h 47m 40s)] Pointers & Memory L89: compare stack vs heap allocation trade-offs — apply to/refine problem #9 with a clear correctness criterion.
90. [Time: 6530s (~1h 48m 50s)] Pointers & Memory L90: build a capstone allocator/container with verified correctness — apply to/refine problem #10 with a clear correctness criterion.
91. [Time: 6600s (~1h 50m)] Pointers & Memory L91: add rigorous NULL/allocation-failure handling — apply to/refine problem #11 with a clear correctness criterion.
92. [Time: 6670s (~1h 51m 10s)] Pointers & Memory L92: eliminate leaks and use-after-free with clear ownership — apply to/refine problem #12 with a clear correctness criterion.
93. [Time: 6740s (~1h 52m 20s)] Pointers & Memory L93: support deep copy and proper destructor/free routines — apply to/refine problem #13 with a clear correctness criterion.
94. [Time: 6810s (~1h 53m 30s)] Pointers & Memory L94: make APIs const-correct and self-documenting — apply to/refine problem #14 with a clear correctness criterion.
95. [Time: 6880s (~1h 54m 40s)] Pointers & Memory L95: handle alignment and strict aliasing safely — apply to/refine problem #15 with a clear correctness criterion.
96. [Time: 6950s (~1h 55m 50s)] Pointers & Memory L96: instrument allocations/frees to detect mismatches — apply to/refine problem #16 with a clear correctness criterion.
97. [Time: 7020s (~1h 57m)] Pointers & Memory L97: generalize with `void*` while preserving type safety patterns — apply to/refine problem #17 with a clear correctness criterion.
98. [Time: 7090s (~1h 58m 10s)] Pointers & Memory L98: stress-test with edge sizes (0, 1, large) and realloc paths — apply to/refine problem #18 with a clear correctness criterion.
99. [Time: 7160s (~1h 59m 20s)] Pointers & Memory L99: compare stack vs heap allocation trade-offs — apply to/refine problem #19 with a clear correctness criterion.
100. [Time: 7230s (~2h 0m 30s)] Pointers & Memory L100: build a capstone allocator/container with verified correctness — apply to/refine problem #20 with a clear correctness criterion.
