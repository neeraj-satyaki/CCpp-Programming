# Bits and Bytes Calculations

## Review Workflow
- Problems are listed in increasing difficulty (1-100).
- Solve one problem at a time in this folder (create your own `.c`/notes files as needed).
- When done, add a note/comment: `DONE: <problem number> - awaiting review`.
- I will review your solution. If it is satisfactory and considered a strong answer, proceed to the next problem.
- If not satisfactory, revise the same problem before moving on.
- **Reset policy (requested):** solutions/files in this track may be reset one by one daily to encourage spaced re-practice. Keep backups of work you want to retain.

---

## Problem Statements

1. [Time: 300s (~5m)] Print binary representation of an unsigned 8-bit value for inputs 0-255.
2. [Time: 370s (~6m 10s)] Print binary representation of a 32-bit unsigned integer without using `%b`.
3. [Time: 440s (~7m 20s)] Check if the kth bit (0-indexed from LSB) of a number is set.
4. [Time: 510s (~8m 30s)] Set, clear, and toggle the kth bit; show before/after values.
5. [Time: 580s (~9m 40s)] Count set bits using a simple loop and shifting.
6. [Time: 650s (~10m 50s)] Count set bits using Brian Kernighan's algorithm.
7. [Time: 720s (~12m)] Check if a number is a power of two using bitwise trick.
8. [Time: 790s (~13m 10s)] Find the position of the lowest set bit.
9. [Time: 860s (~14m 20s)] Isolate the lowest set bit (x & -x) and explain result.
10. [Time: 930s (~15m 30s)] Swap two integers using XOR and discuss when not to use it.
11. [Time: 1000s (~16m 40s)] Compute bitwise AND, OR, XOR, NOT for two integers and display in hex/binary.
12. [Time: 1070s (~17m 50s)] Perform left and right shifts and explain arithmetic vs logical right shift behavior.
13. [Time: 1140s (~19m)] Rotate bits of an 8-bit value left by K and right by K.
14. [Time: 1210s (~20m 10s)] Reverse bits of an unsigned 32-bit integer.
15. [Time: 1280s (~21m 20s)] Extract a bit-field (m bits starting at position p) from an integer.
16. [Time: 1350s (~22m 30s)] Update a bit-field inside an integer with a given value.
17. [Time: 1420s (~23m 40s)] Check parity (even/odd number of set bits) of an integer.
18. [Time: 1490s (~24m 50s)] Convert between binary string and integer value manually.
19. [Time: 1560s (~26m)] Determine endianness of the machine by inspecting a multi-byte integer in memory.
20. [Time: 1630s (~27m 10s)] Compute how many bytes are needed to represent a value (bit-length).
21. [Time: 1700s (~28m 20s)] Pack two 4-bit values into one byte and unpack them.
22. [Time: 1770s (~29m 30s)] Pack date components (day, month, year offset) into minimal bits and unpack.
23. [Time: 1840s (~30m 40s)] Implement a simple checksum (XOR of bytes) for a buffer.
24. [Time: 1910s (~31m 50s)] Detect if adding two unsigned integers will overflow using bit checks.
25. [Time: 1980s (~33m)] Multiply/divide by powers of two using shifts (with caveats).
26. [Time: 2050s (~34m 10s)] Find the only number appearing once when others appear twice (XOR).
27. [Time: 2120s (~35m 20s)] Find two non-repeating numbers when others appear twice using bit partitioning.
28. [Time: 2190s (~36m 30s)] Compute absolute value of an integer using bit tricks (and note portability).
29. [Time: 2260s (~37m 40s)] Compare bitmask-based permission flags (read/write/execute) set/test operations.
30. [Time: 2330s (~38m 50s)] Implement a fixed-size bitmap (set/test/clear) for N flags using an array of bytes.
31. [Time: 2400s (~40m)] Gray code: convert binary to Gray and Gray to binary.
32. [Time: 2470s (~41m 10s)] Count leading zeros of a 32-bit value (without compiler builtin, then compare).
33. [Time: 2540s (~42m 20s)] Round up an integer to next power of two using bit operations.
34. [Time: 2610s (~43m 30s)] Interleave bits of two 16-bit values (Morton code) simple version.
35. [Time: 2680s (~44m 40s)] Implement add-with-carry logic at bit level for two bytes.
36. [Time: 2750s (~45m 50s)] Detect opposite signs of two integers without branching (bit trick).
37. [Time: 2820s (~47m)] Find maximum of two integers without using comparison operators (bit trick).
38. [Time: 2890s (~48m 10s)] Compute Hamming distance between two integers.
39. [Time: 2960s (~49m 20s)] Implement a tiny Bloom-filter-like bit array insert/query (no hashing complexity focus).
40. [Time: 3030s (~50m 30s)] Serialize/deserialize a struct's selected fields into a compact bitstream buffer.
41. [Time: 3100s (~51m 40s)] Bits & Bytes L41: Validate bit positions/ranges and handle invalid inputs safely (extends concept from #1).
42. [Time: 3170s (~52m 50s)] Bits & Bytes L42: Generalize the solution for 8/16/32/64-bit widths (extends concept from #2).
43. [Time: 3240s (~54m)] Bits & Bytes L43: Optimize for fewer operations or branchless execution where safe (extends concept from #3).
44. [Time: 3310s (~55m 10s)] Bits & Bytes L44: Explain and test edge cases (0, all-ones, sign bit/MSB) (extends concept from #4).
45. [Time: 3380s (~56m 20s)] Bits & Bytes L45: Compare naive and optimized approaches with timing (extends concept from #5).
46. [Time: 3450s (~57m 30s)] Bits & Bytes L46: Make the implementation portable across architectures/endianness (extends concept from #6).
47. [Time: 3520s (~58m 40s)] Bits & Bytes L47: Refactor into reusable bit-utility functions/macros with clear contracts (extends concept from #7).
48. [Time: 3590s (~59m 50s)] Bits & Bytes L48: Add visualization of intermediate bit states for debugging (extends concept from #8).
49. [Time: 3660s (~1h 1m)] Bits & Bytes L49: Handle unaligned or variable-length byte buffers robustly (extends concept from #9).
50. [Time: 3730s (~1h 2m 10s)] Bits & Bytes L50: Capstone: build a compact binary protocol encoder/decoder using bit operations (extends concept from #10).
51. [Time: 3800s (~1h 3m 20s)] Bits & Bytes L51: Validate bit positions/ranges and handle invalid inputs safely (extends concept from #11).
52. [Time: 3870s (~1h 4m 30s)] Bits & Bytes L52: Generalize the solution for 8/16/32/64-bit widths (extends concept from #12).
53. [Time: 3940s (~1h 5m 40s)] Bits & Bytes L53: Optimize for fewer operations or branchless execution where safe (extends concept from #13).
54. [Time: 4010s (~1h 6m 50s)] Bits & Bytes L54: Explain and test edge cases (0, all-ones, sign bit/MSB) (extends concept from #14).
55. [Time: 4080s (~1h 8m)] Bits & Bytes L55: Compare naive and optimized approaches with timing (extends concept from #15).
56. [Time: 4150s (~1h 9m 10s)] Bits & Bytes L56: Make the implementation portable across architectures/endianness (extends concept from #16).
57. [Time: 4220s (~1h 10m 20s)] Bits & Bytes L57: Refactor into reusable bit-utility functions/macros with clear contracts (extends concept from #17).
58. [Time: 4290s (~1h 11m 30s)] Bits & Bytes L58: Add visualization of intermediate bit states for debugging (extends concept from #18).
59. [Time: 4360s (~1h 12m 40s)] Bits & Bytes L59: Handle unaligned or variable-length byte buffers robustly (extends concept from #19).
60. [Time: 4430s (~1h 13m 50s)] Bits & Bytes L60: Capstone: build a compact binary protocol encoder/decoder using bit operations (extends concept from #20).
61. [Time: 4500s (~1h 15m)] Bits & Bytes L61: Validate bit positions/ranges and handle invalid inputs safely (extends concept from #21).
62. [Time: 4570s (~1h 16m 10s)] Bits & Bytes L62: Generalize the solution for 8/16/32/64-bit widths (extends concept from #22).
63. [Time: 4640s (~1h 17m 20s)] Bits & Bytes L63: Optimize for fewer operations or branchless execution where safe (extends concept from #23).
64. [Time: 4710s (~1h 18m 30s)] Bits & Bytes L64: Explain and test edge cases (0, all-ones, sign bit/MSB) (extends concept from #24).
65. [Time: 4780s (~1h 19m 40s)] Bits & Bytes L65: Compare naive and optimized approaches with timing (extends concept from #25).
66. [Time: 4850s (~1h 20m 50s)] Bits & Bytes L66: Make the implementation portable across architectures/endianness (extends concept from #26).
67. [Time: 4920s (~1h 22m)] Bits & Bytes L67: Refactor into reusable bit-utility functions/macros with clear contracts (extends concept from #27).
68. [Time: 4990s (~1h 23m 10s)] Bits & Bytes L68: Add visualization of intermediate bit states for debugging (extends concept from #28).
69. [Time: 5060s (~1h 24m 20s)] Bits & Bytes L69: Handle unaligned or variable-length byte buffers robustly (extends concept from #29).
70. [Time: 5130s (~1h 25m 30s)] Bits & Bytes L70: Capstone: build a compact binary protocol encoder/decoder using bit operations (extends concept from #30).
71. [Time: 5200s (~1h 26m 40s)] Bits & Bytes L71: Validate bit positions/ranges and handle invalid inputs safely (extends concept from #31).
72. [Time: 5270s (~1h 27m 50s)] Bits & Bytes L72: Generalize the solution for 8/16/32/64-bit widths (extends concept from #32).
73. [Time: 5340s (~1h 29m)] Bits & Bytes L73: Optimize for fewer operations or branchless execution where safe (extends concept from #33).
74. [Time: 5410s (~1h 30m 10s)] Bits & Bytes L74: Explain and test edge cases (0, all-ones, sign bit/MSB) (extends concept from #34).
75. [Time: 5480s (~1h 31m 20s)] Bits & Bytes L75: Compare naive and optimized approaches with timing (extends concept from #35).
76. [Time: 5550s (~1h 32m 30s)] Bits & Bytes L76: Make the implementation portable across architectures/endianness (extends concept from #36).
77. [Time: 5620s (~1h 33m 40s)] Bits & Bytes L77: Refactor into reusable bit-utility functions/macros with clear contracts (extends concept from #37).
78. [Time: 5690s (~1h 34m 50s)] Bits & Bytes L78: Add visualization of intermediate bit states for debugging (extends concept from #38).
79. [Time: 5760s (~1h 36m)] Bits & Bytes L79: Handle unaligned or variable-length byte buffers robustly (extends concept from #39).
80. [Time: 5830s (~1h 37m 10s)] Bits & Bytes L80: Capstone: build a compact binary protocol encoder/decoder using bit operations (extends concept from #40).
81. [Time: 5900s (~1h 38m 20s)] Bits & Bytes L81: Validate bit positions/ranges and handle invalid inputs safely (extends concept from #1).
82. [Time: 5970s (~1h 39m 30s)] Bits & Bytes L82: Generalize the solution for 8/16/32/64-bit widths (extends concept from #2).
83. [Time: 6040s (~1h 40m 40s)] Bits & Bytes L83: Optimize for fewer operations or branchless execution where safe (extends concept from #3).
84. [Time: 6110s (~1h 41m 50s)] Bits & Bytes L84: Explain and test edge cases (0, all-ones, sign bit/MSB) (extends concept from #4).
85. [Time: 6180s (~1h 43m)] Bits & Bytes L85: Compare naive and optimized approaches with timing (extends concept from #5).
86. [Time: 6250s (~1h 44m 10s)] Bits & Bytes L86: Make the implementation portable across architectures/endianness (extends concept from #6).
87. [Time: 6320s (~1h 45m 20s)] Bits & Bytes L87: Refactor into reusable bit-utility functions/macros with clear contracts (extends concept from #7).
88. [Time: 6390s (~1h 46m 30s)] Bits & Bytes L88: Add visualization of intermediate bit states for debugging (extends concept from #8).
89. [Time: 6460s (~1h 47m 40s)] Bits & Bytes L89: Handle unaligned or variable-length byte buffers robustly (extends concept from #9).
90. [Time: 6530s (~1h 48m 50s)] Bits & Bytes L90: Capstone: build a compact binary protocol encoder/decoder using bit operations (extends concept from #10).
91. [Time: 6600s (~1h 50m)] Bits & Bytes L91: Validate bit positions/ranges and handle invalid inputs safely (extends concept from #11).
92. [Time: 6670s (~1h 51m 10s)] Bits & Bytes L92: Generalize the solution for 8/16/32/64-bit widths (extends concept from #12).
93. [Time: 6740s (~1h 52m 20s)] Bits & Bytes L93: Optimize for fewer operations or branchless execution where safe (extends concept from #13).
94. [Time: 6810s (~1h 53m 30s)] Bits & Bytes L94: Explain and test edge cases (0, all-ones, sign bit/MSB) (extends concept from #14).
95. [Time: 6880s (~1h 54m 40s)] Bits & Bytes L95: Compare naive and optimized approaches with timing (extends concept from #15).
96. [Time: 6950s (~1h 55m 50s)] Bits & Bytes L96: Make the implementation portable across architectures/endianness (extends concept from #16).
97. [Time: 7020s (~1h 57m)] Bits & Bytes L97: Refactor into reusable bit-utility functions/macros with clear contracts (extends concept from #17).
98. [Time: 7090s (~1h 58m 10s)] Bits & Bytes L98: Add visualization of intermediate bit states for debugging (extends concept from #18).
99. [Time: 7160s (~1h 59m 20s)] Bits & Bytes L99: Handle unaligned or variable-length byte buffers robustly (extends concept from #19).
100. [Time: 7230s (~2h 0m 30s)] Bits & Bytes L100: Capstone: build a compact binary protocol encoder/decoder using bit operations (extends concept from #20).
