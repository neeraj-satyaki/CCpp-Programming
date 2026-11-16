# Variables and Data Types

## Review Workflow
- Problems are listed in increasing difficulty (1-100).
- Solve one problem at a time in this folder (create your own `.c`/notes files as needed).
- When done, add a note/comment: `DONE: <problem number> - awaiting review`.
- I will review your solution. If it is satisfactory and considered a strong answer, proceed to the next problem.
- If not satisfactory, revise the same problem before moving on.
- **Reset policy (requested):** solutions/files in this track may be reset one by one daily to encourage spaced re-practice. Keep backups of work you want to retain.

---

## Problem Statements

1. [Time: 300s (~5m)] Declare `int`, `char`, `float`, `double` variables, initialize them, and print with correct format specifiers.
2. [Time: 370s (~6m 10s)] Show sizes (in bytes) of all basic C integer and floating types on your system using `sizeof`.
3. [Time: 440s (~7m 20s)] Demonstrate signed vs unsigned integer overflow/underflow behavior with an example.
4. [Time: 510s (~8m 30s)] Read two integers and print quotient/remainder; explain integer division rules.
5. [Time: 580s (~9m 40s)] Demonstrate implicit type promotion in expressions mixing `char`, `int`, and `double`.
6. [Time: 650s (~10m 50s)] Use explicit casts to control division result and avoid unintended truncation.
7. [Time: 720s (~12m)] Read a character and print its ASCII code; also print next character.
8. [Time: 790s (~13m 10s)] Swap two integers using a temporary variable and show values before/after.
9. [Time: 860s (~14m 20s)] Swap two integers without a temporary variable (arithmetic/XOR) and note limitations.
10. [Time: 930s (~15m 30s)] Demonstrate scope: local variable shadowing a global variable.
11. [Time: 1000s (~16m 40s)] Show lifetime of `static` local variable across multiple function calls.
12. [Time: 1070s (~17m 50s)] Compare `const` variable, pointer-to-const, and const-pointer declarations.
13. [Time: 1140s (~19m)] Demonstrate `enum` as an integer type and print underlying values.
14. [Time: 1210s (~20m 10s)] Use `_Bool`/`stdbool.h` and show logical operations results.
15. [Time: 1280s (~21m 20s)] Parse and print fixed-width integer types from `<stdint.h>` (`int32_t`, `uint64_t`).
16. [Time: 1350s (~22m 30s)] Demonstrate endianness by inspecting bytes of a multi-byte integer.
17. [Time: 1420s (~23m 40s)] Show precision limits of `float` vs `double` with a cumulative sum example.
18. [Time: 1490s (~24m 50s)] Detect and handle invalid numeric input when using `scanf` return values.
19. [Time: 1560s (~26m)] Implement a small program that converts between units using appropriate types.
20. [Time: 1630s (~27m 10s)] Demonstrate `typedef` to create readable aliases for primitive types.
21. [Time: 1700s (~28m 20s)] Use `volatile` in a conceptual example and explain when it's needed.
22. [Time: 1770s (~29m 30s)] Show difference between character literal, string literal, and char array.
23. [Time: 1840s (~30m 40s)] Demonstrate integer promotion pitfalls in bitwise/shift operations on small types.
24. [Time: 1910s (~31m 50s)] Safely compute average of many integers without intermediate overflow.
25. [Time: 1980s (~33m)] Represent money values safely (cents as integer) vs floating-point pitfalls.
26. [Time: 2050s (~34m 10s)] Explore limits from `<limits.h>` and `<float.h>` and print key constants.
27. [Time: 2120s (~35m 20s)] Demonstrate undefined behavior example with signed overflow discussion (do not rely on it).
28. [Time: 2190s (~36m 30s)] Implement saturating addition for unsigned integers.
29. [Time: 2260s (~37m 40s)] Compare alignment/size of structs containing different basic types (intro).
30. [Time: 2330s (~38m 50s)] Write a program that prints a variable's value, address, and size in a formatted report.
31. [Time: 2400s (~40m)] Demonstrate `register` storage class historically and its modern relevance.
32. [Time: 2470s (~41m 10s)] Show how `char` signedness can vary and write portable code.
33. [Time: 2540s (~42m 20s)] Convert between uppercase/lowercase using character arithmetic.
34. [Time: 2610s (~43m 30s)] Demonstrate compound literals for basic types/arrays (C99+).
35. [Time: 2680s (~44m 40s)] Use designated initializers for arrays and observe default zeroing.
36. [Time: 2750s (~45m 50s)] Implement a type-safe input wrapper for integers with range checking.
37. [Time: 2820s (~47m)] Demonstrate narrow vs wide character basics (`char` vs `wchar_t`) printing.
38. [Time: 2890s (~48m 10s)] Show effects of integer truncation when assigning larger type to smaller type.
39. [Time: 2960s (~49m 20s)] Build a mini calculator that selects operation based on a char variable.
40. [Time: 3030s (~50m 30s)] Write a program that serializes basic typed values to a text line and parses them back.
41. [Time: 3100s (~51m 40s)] Variables & Types L41: Add strict input validation and meaningful error reporting (extends concept from #1).
42. [Time: 3170s (~52m 50s)] Variables & Types L42: Handle edge cases (min/max values, zero, negative, empty input) (extends concept from #2).
43. [Time: 3240s (~54m)] Variables & Types L43: Make the solution portable across 32/64-bit platforms (extends concept from #3).
44. [Time: 3310s (~55m 10s)] Variables & Types L44: Refactor into reusable functions with clear type contracts (extends concept from #4).
45. [Time: 3380s (~56m 20s)] Variables & Types L45: Measure and document memory footprint of chosen types (extends concept from #5).
46. [Time: 3450s (~57m 30s)] Variables & Types L46: Prevent undefined behavior and explain the safeguards (extends concept from #6).
47. [Time: 3520s (~58m 40s)] Variables & Types L47: Compare two type choices and justify trade-offs (extends concept from #7).
48. [Time: 3590s (~59m 50s)] Variables & Types L48: Extend to support wider ranges using fixed-width or 64-bit types (extends concept from #8).
49. [Time: 3660s (~1h 1m)] Variables & Types L49: Add robust parsing/formatting with locale/whitespace considerations (extends concept from #9).
50. [Time: 3730s (~1h 2m 10s)] Variables & Types L50: Create a capstone utility combining multiple type-handling techniques (extends concept from #10).
51. [Time: 3800s (~1h 3m 20s)] Variables & Types L51: Add strict input validation and meaningful error reporting (extends concept from #11).
52. [Time: 3870s (~1h 4m 30s)] Variables & Types L52: Handle edge cases (min/max values, zero, negative, empty input) (extends concept from #12).
53. [Time: 3940s (~1h 5m 40s)] Variables & Types L53: Make the solution portable across 32/64-bit platforms (extends concept from #13).
54. [Time: 4010s (~1h 6m 50s)] Variables & Types L54: Refactor into reusable functions with clear type contracts (extends concept from #14).
55. [Time: 4080s (~1h 8m)] Variables & Types L55: Measure and document memory footprint of chosen types (extends concept from #15).
56. [Time: 4150s (~1h 9m 10s)] Variables & Types L56: Prevent undefined behavior and explain the safeguards (extends concept from #16).
57. [Time: 4220s (~1h 10m 20s)] Variables & Types L57: Compare two type choices and justify trade-offs (extends concept from #17).
58. [Time: 4290s (~1h 11m 30s)] Variables & Types L58: Extend to support wider ranges using fixed-width or 64-bit types (extends concept from #18).
59. [Time: 4360s (~1h 12m 40s)] Variables & Types L59: Add robust parsing/formatting with locale/whitespace considerations (extends concept from #19).
60. [Time: 4430s (~1h 13m 50s)] Variables & Types L60: Create a capstone utility combining multiple type-handling techniques (extends concept from #20).
61. [Time: 4500s (~1h 15m)] Variables & Types L61: Add strict input validation and meaningful error reporting (extends concept from #21).
62. [Time: 4570s (~1h 16m 10s)] Variables & Types L62: Handle edge cases (min/max values, zero, negative, empty input) (extends concept from #22).
63. [Time: 4640s (~1h 17m 20s)] Variables & Types L63: Make the solution portable across 32/64-bit platforms (extends concept from #23).
64. [Time: 4710s (~1h 18m 30s)] Variables & Types L64: Refactor into reusable functions with clear type contracts (extends concept from #24).
65. [Time: 4780s (~1h 19m 40s)] Variables & Types L65: Measure and document memory footprint of chosen types (extends concept from #25).
66. [Time: 4850s (~1h 20m 50s)] Variables & Types L66: Prevent undefined behavior and explain the safeguards (extends concept from #26).
67. [Time: 4920s (~1h 22m)] Variables & Types L67: Compare two type choices and justify trade-offs (extends concept from #27).
68. [Time: 4990s (~1h 23m 10s)] Variables & Types L68: Extend to support wider ranges using fixed-width or 64-bit types (extends concept from #28).
69. [Time: 5060s (~1h 24m 20s)] Variables & Types L69: Add robust parsing/formatting with locale/whitespace considerations (extends concept from #29).
70. [Time: 5130s (~1h 25m 30s)] Variables & Types L70: Create a capstone utility combining multiple type-handling techniques (extends concept from #30).
71. [Time: 5200s (~1h 26m 40s)] Variables & Types L71: Add strict input validation and meaningful error reporting (extends concept from #31).
72. [Time: 5270s (~1h 27m 50s)] Variables & Types L72: Handle edge cases (min/max values, zero, negative, empty input) (extends concept from #32).
73. [Time: 5340s (~1h 29m)] Variables & Types L73: Make the solution portable across 32/64-bit platforms (extends concept from #33).
74. [Time: 5410s (~1h 30m 10s)] Variables & Types L74: Refactor into reusable functions with clear type contracts (extends concept from #34).
75. [Time: 5480s (~1h 31m 20s)] Variables & Types L75: Measure and document memory footprint of chosen types (extends concept from #35).
76. [Time: 5550s (~1h 32m 30s)] Variables & Types L76: Prevent undefined behavior and explain the safeguards (extends concept from #36).
77. [Time: 5620s (~1h 33m 40s)] Variables & Types L77: Compare two type choices and justify trade-offs (extends concept from #37).
78. [Time: 5690s (~1h 34m 50s)] Variables & Types L78: Extend to support wider ranges using fixed-width or 64-bit types (extends concept from #38).
79. [Time: 5760s (~1h 36m)] Variables & Types L79: Add robust parsing/formatting with locale/whitespace considerations (extends concept from #39).
80. [Time: 5830s (~1h 37m 10s)] Variables & Types L80: Create a capstone utility combining multiple type-handling techniques (extends concept from #40).
81. [Time: 5900s (~1h 38m 20s)] Variables & Types L81: Add strict input validation and meaningful error reporting (extends concept from #1).
82. [Time: 5970s (~1h 39m 30s)] Variables & Types L82: Handle edge cases (min/max values, zero, negative, empty input) (extends concept from #2).
83. [Time: 6040s (~1h 40m 40s)] Variables & Types L83: Make the solution portable across 32/64-bit platforms (extends concept from #3).
84. [Time: 6110s (~1h 41m 50s)] Variables & Types L84: Refactor into reusable functions with clear type contracts (extends concept from #4).
85. [Time: 6180s (~1h 43m)] Variables & Types L85: Measure and document memory footprint of chosen types (extends concept from #5).
86. [Time: 6250s (~1h 44m 10s)] Variables & Types L86: Prevent undefined behavior and explain the safeguards (extends concept from #6).
87. [Time: 6320s (~1h 45m 20s)] Variables & Types L87: Compare two type choices and justify trade-offs (extends concept from #7).
88. [Time: 6390s (~1h 46m 30s)] Variables & Types L88: Extend to support wider ranges using fixed-width or 64-bit types (extends concept from #8).
89. [Time: 6460s (~1h 47m 40s)] Variables & Types L89: Add robust parsing/formatting with locale/whitespace considerations (extends concept from #9).
90. [Time: 6530s (~1h 48m 50s)] Variables & Types L90: Create a capstone utility combining multiple type-handling techniques (extends concept from #10).
91. [Time: 6600s (~1h 50m)] Variables & Types L91: Add strict input validation and meaningful error reporting (extends concept from #11).
92. [Time: 6670s (~1h 51m 10s)] Variables & Types L92: Handle edge cases (min/max values, zero, negative, empty input) (extends concept from #12).
93. [Time: 6740s (~1h 52m 20s)] Variables & Types L93: Make the solution portable across 32/64-bit platforms (extends concept from #13).
94. [Time: 6810s (~1h 53m 30s)] Variables & Types L94: Refactor into reusable functions with clear type contracts (extends concept from #14).
95. [Time: 6880s (~1h 54m 40s)] Variables & Types L95: Measure and document memory footprint of chosen types (extends concept from #15).
96. [Time: 6950s (~1h 55m 50s)] Variables & Types L96: Prevent undefined behavior and explain the safeguards (extends concept from #16).
97. [Time: 7020s (~1h 57m)] Variables & Types L97: Compare two type choices and justify trade-offs (extends concept from #17).
98. [Time: 7090s (~1h 58m 10s)] Variables & Types L98: Extend to support wider ranges using fixed-width or 64-bit types (extends concept from #18).
99. [Time: 7160s (~1h 59m 20s)] Variables & Types L99: Add robust parsing/formatting with locale/whitespace considerations (extends concept from #19).
100. [Time: 7230s (~2h 0m 30s)] Variables & Types L100: Create a capstone utility combining multiple type-handling techniques (extends concept from #20).
