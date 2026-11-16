# Control Flow

## Review Workflow
- Problems are listed in increasing difficulty (1-100).
- Solve one problem at a time in this folder (create your own `.c`/notes files as needed).
- When done, add a note/comment: `DONE: <problem number> - awaiting review`.
- I will review your solution. If it is satisfactory and considered a strong answer, proceed to the next problem.
- If not satisfactory, revise the same problem before moving on.
- **Reset policy (requested):** solutions/files in this track may be reset one by one daily to encourage spaced re-practice. Keep backups of work you want to retain.

---

## Problem Statements

1. [Time: 300s (~5m)] Print numbers from 1 to N using `for`, `while`, and `do-while` (three variants).
2. [Time: 370s (~6m 10s)] Print multiplication table of N up to 10 in aligned columns.
3. [Time: 440s (~7m 20s)] Sum all even numbers and all odd numbers separately from 1 to N.
4. [Time: 510s (~8m 30s)] Classify a character as vowel, consonant, digit, or special using `if-else` and `switch`.
5. [Time: 580s (~9m 40s)] Build a menu-driven calculator (+,-,*,/,%) that repeats until user exits.
6. [Time: 650s (~10m 50s)] Find all factors of N and count how many are prime.
7. [Time: 720s (~12m)] Check if an integer is a palindrome using loops.
8. [Time: 790s (~13m 10s)] Generate all prime numbers in a range [L, R].
9. [Time: 860s (~14m 20s)] Print a right-angled triangle star pattern of height N.
10. [Time: 930s (~15m 30s)] Print a pyramid/diamond number pattern with correct spacing.
11. [Time: 1000s (~16m 40s)] Compute GCD using repeated subtraction or modulo in a loop.
12. [Time: 1070s (~17m 50s)] Reverse digits of a number; reject non-integer/negative input appropriately.
13. [Time: 1140s (~19m)] Find sum of digits until a single digit remains (digital root) using loops.
14. [Time: 1210s (~20m 10s)] Count frequency of digits (0-9) in a given integer.
15. [Time: 1280s (~21m 20s)] Implement FizzBuzz from 1 to N with customizable divisors.
16. [Time: 1350s (~22m 30s)] Guess-the-number game loop with hints (higher/lower) and attempt limit.
17. [Time: 1420s (~23m 40s)] Simulate an ATM menu (balance, deposit, withdraw) with state variables.
18. [Time: 1490s (~24m 50s)] Validate user input in a loop until it falls within a specified range.
19. [Time: 1560s (~26m)] Print Fibonacci sequence up to N terms with overflow awareness.
20. [Time: 1630s (~27m 10s)] Detect integer overflow risk in iterative factorial loop before multiplying.
21. [Time: 1700s (~28m 20s)] Print Pascal's triangle up to N rows.
22. [Time: 1770s (~29m 30s)] Check whether a number is an Armstrong number for 3-digit and n-digit cases.
23. [Time: 1840s (~30m 40s)] Compute power(x,n) for integer n (including negative n as double) using loops.
24. [Time: 1910s (~31m 50s)] Implement integer binary-to-decimal and decimal-to-binary conversions via control flow.
25. [Time: 1980s (~33m)] Find first N prime numbers (not primes up to N).
26. [Time: 2050s (~34m 10s)] Nested-loop pattern: print a hollow square/rectangle of size N.
27. [Time: 2120s (~35m 20s)] Simulate a simple traffic-light state machine using `enum` and `switch`.
28. [Time: 2190s (~36m 30s)] Count words in a line by iterating characters (handle multiple spaces).
29. [Time: 2260s (~37m 40s)] Remove all vowels from an input string using loops and conditionals.
30. [Time: 2330s (~38m 50s)] Check if brackets in a string are balanced (basic () only) without stack library.
31. [Time: 2400s (~40m)] Implement Collatz sequence steps for a starting number and count steps.
32. [Time: 2470s (~41m 10s)] Find day of week logic or classify date validity with nested conditionals.
33. [Time: 2540s (~42m 20s)] Print all Pythagorean triplets with values <= N.
34. [Time: 2610s (~43m 30s)] Compute sum of series 1 + 1/2 + ... + 1/N with precision control.
35. [Time: 2680s (~44m 40s)] Generate a simple ASCII bar chart from integer values using loops.
36. [Time: 2750s (~45m 50s)] Implement a text-based progress indicator over iterations.
37. [Time: 2820s (~47m)] Search an element in array and report first/last occurrence indices.
38. [Time: 2890s (~48m 10s)] Rotate through menu options cyclically using modulo arithmetic.
39. [Time: 2960s (~49m 20s)] Implement a finite-state input parser (e.g., skip comments/whitespace states).
40. [Time: 3030s (~50m 30s)] Build a loop-based mini REPL that parses simple commands (help/quit/echo).
41. [Time: 3100s (~51m 40s)] Control Flow L41: add robust input validation and retry loops — apply to/refine problem #1 with a clear correctness criterion.
42. [Time: 3170s (~52m 50s)] Control Flow L42: handle edge cases (0, 1, negative, max values) — apply to/refine problem #2 with a clear correctness criterion.
43. [Time: 3240s (~54m)] Control Flow L43: eliminate redundant conditions and simplify logic — apply to/refine problem #3 with a clear correctness criterion.
44. [Time: 3310s (~55m 10s)] Control Flow L44: convert between `for`/`while`/`switch` forms while preserving behavior — apply to/refine problem #4 with a clear correctness criterion.
45. [Time: 3380s (~56m 20s)] Control Flow L45: add clear exit/status codes and user feedback — apply to/refine problem #5 with a clear correctness criterion.
46. [Time: 3450s (~57m 30s)] Control Flow L46: prevent infinite loops with explicit termination guarantees — apply to/refine problem #6 with a clear correctness criterion.
47. [Time: 3520s (~58m 40s)] Control Flow L47: refactor into small functions driven by control flow — apply to/refine problem #7 with a clear correctness criterion.
48. [Time: 3590s (~59m 50s)] Control Flow L48: instrument with counters to observe iterations/comparisons — apply to/refine problem #8 with a clear correctness criterion.
49. [Time: 3660s (~1h 1m)] Control Flow L49: support configurable parameters via user input/flags — apply to/refine problem #9 with a clear correctness criterion.
50. [Time: 3730s (~1h 2m 10s)] Control Flow L50: stress-test with boundary and adversarial inputs — apply to/refine problem #10 with a clear correctness criterion.
51. [Time: 3800s (~1h 3m 20s)] Control Flow L51: add robust input validation and retry loops — apply to/refine problem #11 with a clear correctness criterion.
52. [Time: 3870s (~1h 4m 30s)] Control Flow L52: handle edge cases (0, 1, negative, max values) — apply to/refine problem #12 with a clear correctness criterion.
53. [Time: 3940s (~1h 5m 40s)] Control Flow L53: eliminate redundant conditions and simplify logic — apply to/refine problem #13 with a clear correctness criterion.
54. [Time: 4010s (~1h 6m 50s)] Control Flow L54: convert between `for`/`while`/`switch` forms while preserving behavior — apply to/refine problem #14 with a clear correctness criterion.
55. [Time: 4080s (~1h 8m)] Control Flow L55: add clear exit/status codes and user feedback — apply to/refine problem #15 with a clear correctness criterion.
56. [Time: 4150s (~1h 9m 10s)] Control Flow L56: prevent infinite loops with explicit termination guarantees — apply to/refine problem #16 with a clear correctness criterion.
57. [Time: 4220s (~1h 10m 20s)] Control Flow L57: refactor into small functions driven by control flow — apply to/refine problem #17 with a clear correctness criterion.
58. [Time: 4290s (~1h 11m 30s)] Control Flow L58: instrument with counters to observe iterations/comparisons — apply to/refine problem #18 with a clear correctness criterion.
59. [Time: 4360s (~1h 12m 40s)] Control Flow L59: support configurable parameters via user input/flags — apply to/refine problem #19 with a clear correctness criterion.
60. [Time: 4430s (~1h 13m 50s)] Control Flow L60: stress-test with boundary and adversarial inputs — apply to/refine problem #20 with a clear correctness criterion.
61. [Time: 4500s (~1h 15m)] Control Flow L61: add robust input validation and retry loops — apply to/refine problem #21 with a clear correctness criterion.
62. [Time: 4570s (~1h 16m 10s)] Control Flow L62: handle edge cases (0, 1, negative, max values) — apply to/refine problem #22 with a clear correctness criterion.
63. [Time: 4640s (~1h 17m 20s)] Control Flow L63: eliminate redundant conditions and simplify logic — apply to/refine problem #23 with a clear correctness criterion.
64. [Time: 4710s (~1h 18m 30s)] Control Flow L64: convert between `for`/`while`/`switch` forms while preserving behavior — apply to/refine problem #24 with a clear correctness criterion.
65. [Time: 4780s (~1h 19m 40s)] Control Flow L65: add clear exit/status codes and user feedback — apply to/refine problem #25 with a clear correctness criterion.
66. [Time: 4850s (~1h 20m 50s)] Control Flow L66: prevent infinite loops with explicit termination guarantees — apply to/refine problem #26 with a clear correctness criterion.
67. [Time: 4920s (~1h 22m)] Control Flow L67: refactor into small functions driven by control flow — apply to/refine problem #27 with a clear correctness criterion.
68. [Time: 4990s (~1h 23m 10s)] Control Flow L68: instrument with counters to observe iterations/comparisons — apply to/refine problem #28 with a clear correctness criterion.
69. [Time: 5060s (~1h 24m 20s)] Control Flow L69: support configurable parameters via user input/flags — apply to/refine problem #29 with a clear correctness criterion.
70. [Time: 5130s (~1h 25m 30s)] Control Flow L70: stress-test with boundary and adversarial inputs — apply to/refine problem #30 with a clear correctness criterion.
71. [Time: 5200s (~1h 26m 40s)] Control Flow L71: add robust input validation and retry loops — apply to/refine problem #31 with a clear correctness criterion.
72. [Time: 5270s (~1h 27m 50s)] Control Flow L72: handle edge cases (0, 1, negative, max values) — apply to/refine problem #32 with a clear correctness criterion.
73. [Time: 5340s (~1h 29m)] Control Flow L73: eliminate redundant conditions and simplify logic — apply to/refine problem #33 with a clear correctness criterion.
74. [Time: 5410s (~1h 30m 10s)] Control Flow L74: convert between `for`/`while`/`switch` forms while preserving behavior — apply to/refine problem #34 with a clear correctness criterion.
75. [Time: 5480s (~1h 31m 20s)] Control Flow L75: add clear exit/status codes and user feedback — apply to/refine problem #35 with a clear correctness criterion.
76. [Time: 5550s (~1h 32m 30s)] Control Flow L76: prevent infinite loops with explicit termination guarantees — apply to/refine problem #36 with a clear correctness criterion.
77. [Time: 5620s (~1h 33m 40s)] Control Flow L77: refactor into small functions driven by control flow — apply to/refine problem #37 with a clear correctness criterion.
78. [Time: 5690s (~1h 34m 50s)] Control Flow L78: instrument with counters to observe iterations/comparisons — apply to/refine problem #38 with a clear correctness criterion.
79. [Time: 5760s (~1h 36m)] Control Flow L79: support configurable parameters via user input/flags — apply to/refine problem #39 with a clear correctness criterion.
80. [Time: 5830s (~1h 37m 10s)] Control Flow L80: stress-test with boundary and adversarial inputs — apply to/refine problem #40 with a clear correctness criterion.
81. [Time: 5900s (~1h 38m 20s)] Control Flow L81: add robust input validation and retry loops — apply to/refine problem #1 with a clear correctness criterion.
82. [Time: 5970s (~1h 39m 30s)] Control Flow L82: handle edge cases (0, 1, negative, max values) — apply to/refine problem #2 with a clear correctness criterion.
83. [Time: 6040s (~1h 40m 40s)] Control Flow L83: eliminate redundant conditions and simplify logic — apply to/refine problem #3 with a clear correctness criterion.
84. [Time: 6110s (~1h 41m 50s)] Control Flow L84: convert between `for`/`while`/`switch` forms while preserving behavior — apply to/refine problem #4 with a clear correctness criterion.
85. [Time: 6180s (~1h 43m)] Control Flow L85: add clear exit/status codes and user feedback — apply to/refine problem #5 with a clear correctness criterion.
86. [Time: 6250s (~1h 44m 10s)] Control Flow L86: prevent infinite loops with explicit termination guarantees — apply to/refine problem #6 with a clear correctness criterion.
87. [Time: 6320s (~1h 45m 20s)] Control Flow L87: refactor into small functions driven by control flow — apply to/refine problem #7 with a clear correctness criterion.
88. [Time: 6390s (~1h 46m 30s)] Control Flow L88: instrument with counters to observe iterations/comparisons — apply to/refine problem #8 with a clear correctness criterion.
89. [Time: 6460s (~1h 47m 40s)] Control Flow L89: support configurable parameters via user input/flags — apply to/refine problem #9 with a clear correctness criterion.
90. [Time: 6530s (~1h 48m 50s)] Control Flow L90: stress-test with boundary and adversarial inputs — apply to/refine problem #10 with a clear correctness criterion.
91. [Time: 6600s (~1h 50m)] Control Flow L91: add robust input validation and retry loops — apply to/refine problem #11 with a clear correctness criterion.
92. [Time: 6670s (~1h 51m 10s)] Control Flow L92: handle edge cases (0, 1, negative, max values) — apply to/refine problem #12 with a clear correctness criterion.
93. [Time: 6740s (~1h 52m 20s)] Control Flow L93: eliminate redundant conditions and simplify logic — apply to/refine problem #13 with a clear correctness criterion.
94. [Time: 6810s (~1h 53m 30s)] Control Flow L94: convert between `for`/`while`/`switch` forms while preserving behavior — apply to/refine problem #14 with a clear correctness criterion.
95. [Time: 6880s (~1h 54m 40s)] Control Flow L95: add clear exit/status codes and user feedback — apply to/refine problem #15 with a clear correctness criterion.
96. [Time: 6950s (~1h 55m 50s)] Control Flow L96: prevent infinite loops with explicit termination guarantees — apply to/refine problem #16 with a clear correctness criterion.
97. [Time: 7020s (~1h 57m)] Control Flow L97: refactor into small functions driven by control flow — apply to/refine problem #17 with a clear correctness criterion.
98. [Time: 7090s (~1h 58m 10s)] Control Flow L98: instrument with counters to observe iterations/comparisons — apply to/refine problem #18 with a clear correctness criterion.
99. [Time: 7160s (~1h 59m 20s)] Control Flow L99: support configurable parameters via user input/flags — apply to/refine problem #19 with a clear correctness criterion.
100. [Time: 7230s (~2h 0m 30s)] Control Flow L100: stress-test with boundary and adversarial inputs — apply to/refine problem #20 with a clear correctness criterion.
