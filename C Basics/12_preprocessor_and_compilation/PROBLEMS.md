# Preprocessor and Compilation Stages

## Review Workflow
- Problems are listed in increasing difficulty (1-100).
- Solve one problem at a time in this folder (create your own `.c`/notes files as needed).
- When done, add a note/comment: `DONE: <problem number> - awaiting review`.
- I will review your solution. If it is satisfactory and considered a strong answer, proceed to the next problem.
- If not satisfactory, revise the same problem before moving on.
- **Reset policy (requested):** solutions/files in this track may be reset one by one daily to encourage spaced re-practice. Keep backups of work you want to retain.

---

## Problem Statements

1. [Time: 300s (~5m)] Use `#define` for constants and print them in a program.
2. [Time: 370s (~6m 10s)] Write object-like and function-like macros; observe expansion pitfalls.
3. [Time: 440s (~7m 20s)] Fix macro side-effect bugs using parentheses and `do { } while(0)`.
4. [Time: 510s (~8m 30s)] Use `#ifdef/#ifndef/#endif` to include debug-only code.
5. [Time: 580s (~9m 40s)] Create include guards in a header file and explain purpose.
6. [Time: 650s (~10m 50s)] Split a program into multiple `.c` and `.h` files and compile together.
7. [Time: 720s (~12m)] Use `gcc -E` to inspect preprocessed output for macros/includes.
8. [Time: 790s (~13m 10s)] Use `gcc -S` to generate assembly and identify function prologue/epilogue conceptually.
9. [Time: 860s (~14m 20s)] Use `gcc -c` to produce object files and link them in a separate step.
10. [Time: 930s (~15m 30s)] Demonstrate difference between declaration (header) and definition (source).
11. [Time: 1000s (~16m 40s)] Use predefined macros like `__FILE__`, `__LINE__`, `__DATE__`, `__TIME__` for logging.
12. [Time: 1070s (~17m 50s)] Implement a simple logging macro with log levels controlled by compile-time flag.
13. [Time: 1140s (~19m)] Use `#pragma once` vs include guards; discuss portability.
14. [Time: 1210s (~20m 10s)] Conditional compilation for platform-specific code (e.g., Linux checks).
15. [Time: 1280s (~21m 20s)] Create a macro-based generic min/max and analyze type issues.
16. [Time: 1350s (~22m 30s)] Understand header dependency chains and reduce unnecessary includes.
17. [Time: 1420s (~23m 40s)] Demonstrate `static` functions/variables at file scope for internal linkage.
18. [Time: 1490s (~24m 50s)] Use `extern` to share global variable across translation units correctly.
19. [Time: 1560s (~26m)] Create and use a simple static inline helper in header (C99).
20. [Time: 1630s (~27m 10s)] Explore effect of optimization flags (-O0 vs -O2) on generated assembly (observation).
21. [Time: 1700s (~28m 20s)] Demonstrate separate compilation benefits when changing one source file.
22. [Time: 1770s (~29m 30s)] Use `-Wall -Wextra -Werror` and fix resulting diagnostics in sample code.
23. [Time: 1840s (~30m 40s)] Generate dependency files (`-MMD -MP`) conceptually and explain their role.
24. [Time: 1910s (~31m 50s)] Show name mangling absence in C and linkage basics with `nm` on objects.
25. [Time: 1980s (~33m)] Build with different C standards (`-std=c11`, etc.) and note differences.
26. [Time: 2050s (~34m 10s)] Use `#error` and `#warning` (where supported) for build-time checks.
27. [Time: 2120s (~35m 20s)] Stringification (`#`) and token pasting (`##`) in macros with examples.
28. [Time: 2190s (~36m 30s)] Create configurable feature flags via macros passed from compiler (`-D`).
29. [Time: 2260s (~37m 40s)] Understand translation units and one-definition rule issues in C projects.
30. [Time: 2330s (~38m 50s)] Produce map/symbol insights via linker flags conceptually (project-level).
31. [Time: 2400s (~40m)] Organize a small project directory for headers/sources/build outputs.
32. [Time: 2470s (~41m 10s)] Demonstrate reproducible builds considerations (timestamps/macros).
33. [Time: 2540s (~42m 20s)] Compare macro-based generics vs `_Generic` (C11) for a simple case.
34. [Time: 2610s (~43m 30s)] Precompiled headers concept: when useful and trade-offs (documented exercise).
35. [Time: 2680s (~44m 40s)] Cross-compilation basics: what changes in toolchain/flags (conceptual).
36. [Time: 2750s (~45m 50s)] Use `pkg-config` style flags conceptually when compiling against libs.
37. [Time: 2820s (~47m)] Detect and resolve multiple definition linker errors from headers.
38. [Time: 2890s (~48m 10s)] Build a tiny library and app showing compile vs link dependencies.
39. [Time: 2960s (~49m 20s)] Automate multi-step compilation with a shell script before Make.
40. [Time: 3030s (~50m 30s)] Capstone: design a clean multi-module C project layout with headers, macros, logging, and documented build stages.
41. [Time: 3100s (~51m 40s)] Preprocessor & Compilation L41: add clear module boundaries and include hygiene — apply to/refine problem #1 with a clear correctness criterion.
42. [Time: 3170s (~52m 50s)] Preprocessor & Compilation L42: eliminate macro hazards and prefer safer alternatives — apply to/refine problem #2 with a clear correctness criterion.
43. [Time: 3240s (~54m)] Preprocessor & Compilation L43: make builds reproducible and warning-clean — apply to/refine problem #3 with a clear correctness criterion.
44. [Time: 3310s (~55m 10s)] Preprocessor & Compilation L44: support debug/release/profile configurations via flags — apply to/refine problem #4 with a clear correctness criterion.
45. [Time: 3380s (~56m 20s)] Preprocessor & Compilation L45: document each compilation/link stage and artifacts — apply to/refine problem #5 with a clear correctness criterion.
46. [Time: 3450s (~57m 30s)] Preprocessor & Compilation L46: ensure portability across compilers/standards where possible — apply to/refine problem #6 with a clear correctness criterion.
47. [Time: 3520s (~58m 40s)] Preprocessor & Compilation L47: reduce compile times via dependency minimization — apply to/refine problem #7 with a clear correctness criterion.
48. [Time: 3590s (~59m 50s)] Preprocessor & Compilation L48: add automated checks for style/warnings — apply to/refine problem #8 with a clear correctness criterion.
49. [Time: 3660s (~1h 1m)] Preprocessor & Compilation L49: handle third-party headers/libs integration cleanly — apply to/refine problem #9 with a clear correctness criterion.
50. [Time: 3730s (~1h 2m 10s)] Preprocessor & Compilation L50: capstone: produce a polished build-ready project template — apply to/refine problem #10 with a clear correctness criterion.
51. [Time: 3800s (~1h 3m 20s)] Preprocessor & Compilation L51: add clear module boundaries and include hygiene — apply to/refine problem #11 with a clear correctness criterion.
52. [Time: 3870s (~1h 4m 30s)] Preprocessor & Compilation L52: eliminate macro hazards and prefer safer alternatives — apply to/refine problem #12 with a clear correctness criterion.
53. [Time: 3940s (~1h 5m 40s)] Preprocessor & Compilation L53: make builds reproducible and warning-clean — apply to/refine problem #13 with a clear correctness criterion.
54. [Time: 4010s (~1h 6m 50s)] Preprocessor & Compilation L54: support debug/release/profile configurations via flags — apply to/refine problem #14 with a clear correctness criterion.
55. [Time: 4080s (~1h 8m)] Preprocessor & Compilation L55: document each compilation/link stage and artifacts — apply to/refine problem #15 with a clear correctness criterion.
56. [Time: 4150s (~1h 9m 10s)] Preprocessor & Compilation L56: ensure portability across compilers/standards where possible — apply to/refine problem #16 with a clear correctness criterion.
57. [Time: 4220s (~1h 10m 20s)] Preprocessor & Compilation L57: reduce compile times via dependency minimization — apply to/refine problem #17 with a clear correctness criterion.
58. [Time: 4290s (~1h 11m 30s)] Preprocessor & Compilation L58: add automated checks for style/warnings — apply to/refine problem #18 with a clear correctness criterion.
59. [Time: 4360s (~1h 12m 40s)] Preprocessor & Compilation L59: handle third-party headers/libs integration cleanly — apply to/refine problem #19 with a clear correctness criterion.
60. [Time: 4430s (~1h 13m 50s)] Preprocessor & Compilation L60: capstone: produce a polished build-ready project template — apply to/refine problem #20 with a clear correctness criterion.
61. [Time: 4500s (~1h 15m)] Preprocessor & Compilation L61: add clear module boundaries and include hygiene — apply to/refine problem #21 with a clear correctness criterion.
62. [Time: 4570s (~1h 16m 10s)] Preprocessor & Compilation L62: eliminate macro hazards and prefer safer alternatives — apply to/refine problem #22 with a clear correctness criterion.
63. [Time: 4640s (~1h 17m 20s)] Preprocessor & Compilation L63: make builds reproducible and warning-clean — apply to/refine problem #23 with a clear correctness criterion.
64. [Time: 4710s (~1h 18m 30s)] Preprocessor & Compilation L64: support debug/release/profile configurations via flags — apply to/refine problem #24 with a clear correctness criterion.
65. [Time: 4780s (~1h 19m 40s)] Preprocessor & Compilation L65: document each compilation/link stage and artifacts — apply to/refine problem #25 with a clear correctness criterion.
66. [Time: 4850s (~1h 20m 50s)] Preprocessor & Compilation L66: ensure portability across compilers/standards where possible — apply to/refine problem #26 with a clear correctness criterion.
67. [Time: 4920s (~1h 22m)] Preprocessor & Compilation L67: reduce compile times via dependency minimization — apply to/refine problem #27 with a clear correctness criterion.
68. [Time: 4990s (~1h 23m 10s)] Preprocessor & Compilation L68: add automated checks for style/warnings — apply to/refine problem #28 with a clear correctness criterion.
69. [Time: 5060s (~1h 24m 20s)] Preprocessor & Compilation L69: handle third-party headers/libs integration cleanly — apply to/refine problem #29 with a clear correctness criterion.
70. [Time: 5130s (~1h 25m 30s)] Preprocessor & Compilation L70: capstone: produce a polished build-ready project template — apply to/refine problem #30 with a clear correctness criterion.
71. [Time: 5200s (~1h 26m 40s)] Preprocessor & Compilation L71: add clear module boundaries and include hygiene — apply to/refine problem #31 with a clear correctness criterion.
72. [Time: 5270s (~1h 27m 50s)] Preprocessor & Compilation L72: eliminate macro hazards and prefer safer alternatives — apply to/refine problem #32 with a clear correctness criterion.
73. [Time: 5340s (~1h 29m)] Preprocessor & Compilation L73: make builds reproducible and warning-clean — apply to/refine problem #33 with a clear correctness criterion.
74. [Time: 5410s (~1h 30m 10s)] Preprocessor & Compilation L74: support debug/release/profile configurations via flags — apply to/refine problem #34 with a clear correctness criterion.
75. [Time: 5480s (~1h 31m 20s)] Preprocessor & Compilation L75: document each compilation/link stage and artifacts — apply to/refine problem #35 with a clear correctness criterion.
76. [Time: 5550s (~1h 32m 30s)] Preprocessor & Compilation L76: ensure portability across compilers/standards where possible — apply to/refine problem #36 with a clear correctness criterion.
77. [Time: 5620s (~1h 33m 40s)] Preprocessor & Compilation L77: reduce compile times via dependency minimization — apply to/refine problem #37 with a clear correctness criterion.
78. [Time: 5690s (~1h 34m 50s)] Preprocessor & Compilation L78: add automated checks for style/warnings — apply to/refine problem #38 with a clear correctness criterion.
79. [Time: 5760s (~1h 36m)] Preprocessor & Compilation L79: handle third-party headers/libs integration cleanly — apply to/refine problem #39 with a clear correctness criterion.
80. [Time: 5830s (~1h 37m 10s)] Preprocessor & Compilation L80: capstone: produce a polished build-ready project template — apply to/refine problem #40 with a clear correctness criterion.
81. [Time: 5900s (~1h 38m 20s)] Preprocessor & Compilation L81: add clear module boundaries and include hygiene — apply to/refine problem #1 with a clear correctness criterion.
82. [Time: 5970s (~1h 39m 30s)] Preprocessor & Compilation L82: eliminate macro hazards and prefer safer alternatives — apply to/refine problem #2 with a clear correctness criterion.
83. [Time: 6040s (~1h 40m 40s)] Preprocessor & Compilation L83: make builds reproducible and warning-clean — apply to/refine problem #3 with a clear correctness criterion.
84. [Time: 6110s (~1h 41m 50s)] Preprocessor & Compilation L84: support debug/release/profile configurations via flags — apply to/refine problem #4 with a clear correctness criterion.
85. [Time: 6180s (~1h 43m)] Preprocessor & Compilation L85: document each compilation/link stage and artifacts — apply to/refine problem #5 with a clear correctness criterion.
86. [Time: 6250s (~1h 44m 10s)] Preprocessor & Compilation L86: ensure portability across compilers/standards where possible — apply to/refine problem #6 with a clear correctness criterion.
87. [Time: 6320s (~1h 45m 20s)] Preprocessor & Compilation L87: reduce compile times via dependency minimization — apply to/refine problem #7 with a clear correctness criterion.
88. [Time: 6390s (~1h 46m 30s)] Preprocessor & Compilation L88: add automated checks for style/warnings — apply to/refine problem #8 with a clear correctness criterion.
89. [Time: 6460s (~1h 47m 40s)] Preprocessor & Compilation L89: handle third-party headers/libs integration cleanly — apply to/refine problem #9 with a clear correctness criterion.
90. [Time: 6530s (~1h 48m 50s)] Preprocessor & Compilation L90: capstone: produce a polished build-ready project template — apply to/refine problem #10 with a clear correctness criterion.
91. [Time: 6600s (~1h 50m)] Preprocessor & Compilation L91: add clear module boundaries and include hygiene — apply to/refine problem #11 with a clear correctness criterion.
92. [Time: 6670s (~1h 51m 10s)] Preprocessor & Compilation L92: eliminate macro hazards and prefer safer alternatives — apply to/refine problem #12 with a clear correctness criterion.
93. [Time: 6740s (~1h 52m 20s)] Preprocessor & Compilation L93: make builds reproducible and warning-clean — apply to/refine problem #13 with a clear correctness criterion.
94. [Time: 6810s (~1h 53m 30s)] Preprocessor & Compilation L94: support debug/release/profile configurations via flags — apply to/refine problem #14 with a clear correctness criterion.
95. [Time: 6880s (~1h 54m 40s)] Preprocessor & Compilation L95: document each compilation/link stage and artifacts — apply to/refine problem #15 with a clear correctness criterion.
96. [Time: 6950s (~1h 55m 50s)] Preprocessor & Compilation L96: ensure portability across compilers/standards where possible — apply to/refine problem #16 with a clear correctness criterion.
97. [Time: 7020s (~1h 57m)] Preprocessor & Compilation L97: reduce compile times via dependency minimization — apply to/refine problem #17 with a clear correctness criterion.
98. [Time: 7090s (~1h 58m 10s)] Preprocessor & Compilation L98: add automated checks for style/warnings — apply to/refine problem #18 with a clear correctness criterion.
99. [Time: 7160s (~1h 59m 20s)] Preprocessor & Compilation L99: handle third-party headers/libs integration cleanly — apply to/refine problem #19 with a clear correctness criterion.
100. [Time: 7230s (~2h 0m 30s)] Preprocessor & Compilation L100: capstone: produce a polished build-ready project template — apply to/refine problem #20 with a clear correctness criterion.
