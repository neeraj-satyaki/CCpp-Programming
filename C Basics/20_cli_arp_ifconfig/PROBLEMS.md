# Recreating `arp`/`ifconfig`-like CLI Tools in C

## Review Workflow
- Problems are listed in increasing difficulty (1-100).
- Solve one problem at a time in this folder (create your own `.c`/notes files as needed).
- When done, add a note/comment: `DONE: <problem number> - awaiting review`.
- I will review your solution. If it is satisfactory and considered a strong answer, proceed to the next problem.
- If not satisfactory, revise the same problem before moving on.
- **Reset policy (requested):** solutions/files in this track may be reset one by one daily to encourage spaced re-practice. Keep backups of work you want to retain.

---

## Problem Statements

1. [Time: 300s (~5m)] List network interface names on Linux (via `/sys/class/net` or getifaddrs).
2. [Time: 370s (~6m 10s)] Display basic interface summary (name, up/down status).
3. [Time: 440s (~7m 20s)] Fetch and print MAC address for an interface using ioctl/getifaddrs.
4. [Time: 510s (~8m 30s)] Fetch and print IPv4 addresses for interfaces.
5. [Time: 580s (~9m 40s)] Fetch and print IPv6 addresses for interfaces (where available).
6. [Time: 650s (~10m 50s)] Display MTU and interface flags in human-readable form.
7. [Time: 720s (~12m)] Implement an `ifconfig`-like all-interfaces overview output.
8. [Time: 790s (~13m 10s)] Select and display details for a single interface by name.
9. [Time: 860s (~14m 20s)] Read ARP/neighbour table from `/proc/net/arp`.
10. [Time: 930s (~15m 30s)] Parse and print ARP entries in aligned columns.
11. [Time: 1000s (~16m 40s)] Filter ARP entries by interface name.
12. [Time: 1070s (~17m 50s)] Filter ARP entries by IP/MAC pattern (simple match).
13. [Time: 1140s (~19m)] Handle systems/files where ARP info is unavailable with clear errors.
14. [Time: 1210s (~20m 10s)] Show RX/TX packet/byte statistics from `/proc/net/dev`.
15. [Time: 1280s (~21m 20s)] Combine interface config and stats into one report view.
16. [Time: 1350s (~22m 30s)] Add command-line options for choosing mode (interfaces/arp/stats).
17. [Time: 1420s (~23m 40s)] Implement `--help` and usage with examples.
18. [Time: 1490s (~24m 50s)] Detect permissions/capabilities needed for certain operations and report gracefully.
19. [Time: 1560s (~26m)] Support numeric vs resolved names display (where applicable, or document).
20. [Time: 1630s (~27m 10s)] Sort interface and ARP outputs consistently.
21. [Time: 1700s (~28m 20s)] Handle interfaces with no assigned addresses.
22. [Time: 1770s (~29m 30s)] Display loopback and virtual interfaces distinctly.
23. [Time: 1840s (~30m 40s)] Parse flags like UP, BROADCAST, RUNNING, MULTICAST into labels.
24. [Time: 1910s (~31m 50s)] Implement JSON-like or machine-readable output option (simple).
25. [Time: 1980s (~33m)] Refresh/display live stats in a loop at interval (basic monitor).
26. [Time: 2050s (~34m 10s)] Compute deltas in RX/TX counters between intervals.
27. [Time: 2120s (~35m 20s)] Support multiple targets/interfaces as arguments.
28. [Time: 2190s (~36m 30s)] Validate interface names and provide suggestions on typos (optional).
29. [Time: 2260s (~37m 40s)] Compare outputs with `ip addr`/`ifconfig`/`arp` and document differences.
30. [Time: 2330s (~38m 50s)] Abstract data collection behind functions per source (procfs/ioctl/netlink concept).
31. [Time: 2400s (~40m)] Use `getifaddrs` as primary API and fall back where needed.
32. [Time: 2470s (~41m 10s)] Handle IPv6 formatting and scope IDs correctly.
33. [Time: 2540s (~42m 20s)] Parse neighbour state/flags if available from other sources (document).
34. [Time: 2610s (~43m 30s)] Robustly handle malformed/unexpected procfs content.
35. [Time: 2680s (~44m 40s)] Unit-test parsing functions with sample procfs strings/files.
36. [Time: 2750s (~45m 50s)] Ensure safe string handling and fixed buffers are avoided/checked.
37. [Time: 2820s (~47m)] Support cross-platform notes: Linux implementation with graceful non-Linux stubs/messages.
38. [Time: 2890s (~48m 10s)] Add verbose/debug mode showing data sources used.
39. [Time: 2960s (~49m 20s)] Package as a single CLI with subcommands (`myifconfig`, `myarp` modes).
40. [Time: 3030s (~50m 30s)] Capstone: implement a polished network-info CLI (ifconfig+arp subset) with clear options, robust parsing, and documented Linux-focused behavior.
41. [Time: 3100s (~51m 40s)] CLI arp/ifconfig L41: improve parsing robustness and source fallbacks — apply to/refine problem #1 with a clear correctness criterion.
42. [Time: 3170s (~52m 50s)] CLI arp/ifconfig L42: add clearer formatting and user-friendly output — apply to/refine problem #2 with a clear correctness criterion.
43. [Time: 3240s (~54m)] CLI arp/ifconfig L43: support more fields/options with accurate semantics — apply to/refine problem #3 with a clear correctness criterion.
44. [Time: 3310s (~55m 10s)] CLI arp/ifconfig L44: handle permissions and platform limitations gracefully — apply to/refine problem #4 with a clear correctness criterion.
45. [Time: 3380s (~56m 20s)] CLI arp/ifconfig L45: refactor data collection vs presentation layers — apply to/refine problem #5 with a clear correctness criterion.
46. [Time: 3450s (~57m 30s)] CLI arp/ifconfig L46: add tests with fixture inputs for parsers — apply to/refine problem #6 with a clear correctness criterion.
47. [Time: 3520s (~58m 40s)] CLI arp/ifconfig L47: optimize for low overhead in monitoring mode — apply to/refine problem #7 with a clear correctness criterion.
48. [Time: 3590s (~59m 50s)] CLI arp/ifconfig L48: document differences from standard tools explicitly — apply to/refine problem #8 with a clear correctness criterion.
49. [Time: 3660s (~1h 1m)] CLI arp/ifconfig L49: ensure safe memory/string handling throughout — apply to/refine problem #9 with a clear correctness criterion.
50. [Time: 3730s (~1h 2m 10s)] CLI arp/ifconfig L50: capstone: deliver a dependable, well-documented CLI tool subset — apply to/refine problem #10 with a clear correctness criterion.
51. [Time: 3800s (~1h 3m 20s)] CLI arp/ifconfig L51: improve parsing robustness and source fallbacks — apply to/refine problem #11 with a clear correctness criterion.
52. [Time: 3870s (~1h 4m 30s)] CLI arp/ifconfig L52: add clearer formatting and user-friendly output — apply to/refine problem #12 with a clear correctness criterion.
53. [Time: 3940s (~1h 5m 40s)] CLI arp/ifconfig L53: support more fields/options with accurate semantics — apply to/refine problem #13 with a clear correctness criterion.
54. [Time: 4010s (~1h 6m 50s)] CLI arp/ifconfig L54: handle permissions and platform limitations gracefully — apply to/refine problem #14 with a clear correctness criterion.
55. [Time: 4080s (~1h 8m)] CLI arp/ifconfig L55: refactor data collection vs presentation layers — apply to/refine problem #15 with a clear correctness criterion.
56. [Time: 4150s (~1h 9m 10s)] CLI arp/ifconfig L56: add tests with fixture inputs for parsers — apply to/refine problem #16 with a clear correctness criterion.
57. [Time: 4220s (~1h 10m 20s)] CLI arp/ifconfig L57: optimize for low overhead in monitoring mode — apply to/refine problem #17 with a clear correctness criterion.
58. [Time: 4290s (~1h 11m 30s)] CLI arp/ifconfig L58: document differences from standard tools explicitly — apply to/refine problem #18 with a clear correctness criterion.
59. [Time: 4360s (~1h 12m 40s)] CLI arp/ifconfig L59: ensure safe memory/string handling throughout — apply to/refine problem #19 with a clear correctness criterion.
60. [Time: 4430s (~1h 13m 50s)] CLI arp/ifconfig L60: capstone: deliver a dependable, well-documented CLI tool subset — apply to/refine problem #20 with a clear correctness criterion.
61. [Time: 4500s (~1h 15m)] CLI arp/ifconfig L61: improve parsing robustness and source fallbacks — apply to/refine problem #21 with a clear correctness criterion.
62. [Time: 4570s (~1h 16m 10s)] CLI arp/ifconfig L62: add clearer formatting and user-friendly output — apply to/refine problem #22 with a clear correctness criterion.
63. [Time: 4640s (~1h 17m 20s)] CLI arp/ifconfig L63: support more fields/options with accurate semantics — apply to/refine problem #23 with a clear correctness criterion.
64. [Time: 4710s (~1h 18m 30s)] CLI arp/ifconfig L64: handle permissions and platform limitations gracefully — apply to/refine problem #24 with a clear correctness criterion.
65. [Time: 4780s (~1h 19m 40s)] CLI arp/ifconfig L65: refactor data collection vs presentation layers — apply to/refine problem #25 with a clear correctness criterion.
66. [Time: 4850s (~1h 20m 50s)] CLI arp/ifconfig L66: add tests with fixture inputs for parsers — apply to/refine problem #26 with a clear correctness criterion.
67. [Time: 4920s (~1h 22m)] CLI arp/ifconfig L67: optimize for low overhead in monitoring mode — apply to/refine problem #27 with a clear correctness criterion.
68. [Time: 4990s (~1h 23m 10s)] CLI arp/ifconfig L68: document differences from standard tools explicitly — apply to/refine problem #28 with a clear correctness criterion.
69. [Time: 5060s (~1h 24m 20s)] CLI arp/ifconfig L69: ensure safe memory/string handling throughout — apply to/refine problem #29 with a clear correctness criterion.
70. [Time: 5130s (~1h 25m 30s)] CLI arp/ifconfig L70: capstone: deliver a dependable, well-documented CLI tool subset — apply to/refine problem #30 with a clear correctness criterion.
71. [Time: 5200s (~1h 26m 40s)] CLI arp/ifconfig L71: improve parsing robustness and source fallbacks — apply to/refine problem #31 with a clear correctness criterion.
72. [Time: 5270s (~1h 27m 50s)] CLI arp/ifconfig L72: add clearer formatting and user-friendly output — apply to/refine problem #32 with a clear correctness criterion.
73. [Time: 5340s (~1h 29m)] CLI arp/ifconfig L73: support more fields/options with accurate semantics — apply to/refine problem #33 with a clear correctness criterion.
74. [Time: 5410s (~1h 30m 10s)] CLI arp/ifconfig L74: handle permissions and platform limitations gracefully — apply to/refine problem #34 with a clear correctness criterion.
75. [Time: 5480s (~1h 31m 20s)] CLI arp/ifconfig L75: refactor data collection vs presentation layers — apply to/refine problem #35 with a clear correctness criterion.
76. [Time: 5550s (~1h 32m 30s)] CLI arp/ifconfig L76: add tests with fixture inputs for parsers — apply to/refine problem #36 with a clear correctness criterion.
77. [Time: 5620s (~1h 33m 40s)] CLI arp/ifconfig L77: optimize for low overhead in monitoring mode — apply to/refine problem #37 with a clear correctness criterion.
78. [Time: 5690s (~1h 34m 50s)] CLI arp/ifconfig L78: document differences from standard tools explicitly — apply to/refine problem #38 with a clear correctness criterion.
79. [Time: 5760s (~1h 36m)] CLI arp/ifconfig L79: ensure safe memory/string handling throughout — apply to/refine problem #39 with a clear correctness criterion.
80. [Time: 5830s (~1h 37m 10s)] CLI arp/ifconfig L80: capstone: deliver a dependable, well-documented CLI tool subset — apply to/refine problem #40 with a clear correctness criterion.
81. [Time: 5900s (~1h 38m 20s)] CLI arp/ifconfig L81: improve parsing robustness and source fallbacks — apply to/refine problem #1 with a clear correctness criterion.
82. [Time: 5970s (~1h 39m 30s)] CLI arp/ifconfig L82: add clearer formatting and user-friendly output — apply to/refine problem #2 with a clear correctness criterion.
83. [Time: 6040s (~1h 40m 40s)] CLI arp/ifconfig L83: support more fields/options with accurate semantics — apply to/refine problem #3 with a clear correctness criterion.
84. [Time: 6110s (~1h 41m 50s)] CLI arp/ifconfig L84: handle permissions and platform limitations gracefully — apply to/refine problem #4 with a clear correctness criterion.
85. [Time: 6180s (~1h 43m)] CLI arp/ifconfig L85: refactor data collection vs presentation layers — apply to/refine problem #5 with a clear correctness criterion.
86. [Time: 6250s (~1h 44m 10s)] CLI arp/ifconfig L86: add tests with fixture inputs for parsers — apply to/refine problem #6 with a clear correctness criterion.
87. [Time: 6320s (~1h 45m 20s)] CLI arp/ifconfig L87: optimize for low overhead in monitoring mode — apply to/refine problem #7 with a clear correctness criterion.
88. [Time: 6390s (~1h 46m 30s)] CLI arp/ifconfig L88: document differences from standard tools explicitly — apply to/refine problem #8 with a clear correctness criterion.
89. [Time: 6460s (~1h 47m 40s)] CLI arp/ifconfig L89: ensure safe memory/string handling throughout — apply to/refine problem #9 with a clear correctness criterion.
90. [Time: 6530s (~1h 48m 50s)] CLI arp/ifconfig L90: capstone: deliver a dependable, well-documented CLI tool subset — apply to/refine problem #10 with a clear correctness criterion.
91. [Time: 6600s (~1h 50m)] CLI arp/ifconfig L91: improve parsing robustness and source fallbacks — apply to/refine problem #11 with a clear correctness criterion.
92. [Time: 6670s (~1h 51m 10s)] CLI arp/ifconfig L92: add clearer formatting and user-friendly output — apply to/refine problem #12 with a clear correctness criterion.
93. [Time: 6740s (~1h 52m 20s)] CLI arp/ifconfig L93: support more fields/options with accurate semantics — apply to/refine problem #13 with a clear correctness criterion.
94. [Time: 6810s (~1h 53m 30s)] CLI arp/ifconfig L94: handle permissions and platform limitations gracefully — apply to/refine problem #14 with a clear correctness criterion.
95. [Time: 6880s (~1h 54m 40s)] CLI arp/ifconfig L95: refactor data collection vs presentation layers — apply to/refine problem #15 with a clear correctness criterion.
96. [Time: 6950s (~1h 55m 50s)] CLI arp/ifconfig L96: add tests with fixture inputs for parsers — apply to/refine problem #16 with a clear correctness criterion.
97. [Time: 7020s (~1h 57m)] CLI arp/ifconfig L97: optimize for low overhead in monitoring mode — apply to/refine problem #17 with a clear correctness criterion.
98. [Time: 7090s (~1h 58m 10s)] CLI arp/ifconfig L98: document differences from standard tools explicitly — apply to/refine problem #18 with a clear correctness criterion.
99. [Time: 7160s (~1h 59m 20s)] CLI arp/ifconfig L99: ensure safe memory/string handling throughout — apply to/refine problem #19 with a clear correctness criterion.
100. [Time: 7230s (~2h 0m 30s)] CLI arp/ifconfig L100: capstone: deliver a dependable, well-documented CLI tool subset — apply to/refine problem #20 with a clear correctness criterion.
