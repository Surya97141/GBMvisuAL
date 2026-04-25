<div align="center">

<br>

```
 ██████╗ ██████╗ ███╗   ███╗██╗   ██╗██╗███████╗██╗   ██╗ █████╗ ██╗
██╔════╝ ██╔══██╗████╗ ████║██║   ██║██║██╔════╝██║   ██║██╔══██╗██║
██║  ███╗██████╔╝██╔████╔██║██║   ██║██║███████╗██║   ██║███████║██║
██║   ██║██╔══██╗██║╚██╔╝██║╚██╗ ██╔╝██║╚════██║██║   ██║██╔══██║██║
╚██████╔╝██████╔╝██║ ╚═╝ ██║ ╚████╔╝ ██║███████║╚██████╔╝██║  ██║███████╗
 ╚═════╝ ╚═════╝ ╚═╝     ╚═╝  ╚═══╝  ╚═╝╚══════╝ ╚═════╝ ╚═╝  ╚═╝╚══════╝
```

<h3>Algorithm Visualizer Library</h3>
<p><em>Watch code think in real time. Step by step. No diagrams. No videos. No pseudocode.</em></p>

<br>

[![Live](https://img.shields.io/badge/LIVE%20NOW-gbmvisual.vercel.app-06d6a0?style=for-the-badge&labelColor=0d0d18)](https://gbmvisual.vercel.app)

<br>

![Visualizers](https://img.shields.io/badge/Live%20Visualizers-70%2B-06d6a0?style=flat-square&labelColor=13131f)
![Categories](https://img.shields.io/badge/Categories-50-ffd166?style=flat-square&labelColor=13131f)
![Problems](https://img.shields.io/badge/Problems-470-c084fc?style=flat-square&labelColor=13131f)
![Dependencies](https://img.shields.io/badge/Dependencies-0-e63946?style=flat-square&labelColor=13131f)
![License](https://img.shields.io/badge/License-MIT-2196f3?style=flat-square&labelColor=13131f)

</div>

---

<br>

## The idea

Most algorithm content teaches you the *what*. GBMvisuAL teaches you the *why it works*.

Every visualizer is a hand-crafted, step-by-step interactive animation. You see the data structure mutate. You see the exact decision being made. You see which condition caused that decision. You press a button to go one step at a time, or let it play at your speed.

Not a video. Not a GIF. Not a Jupyter notebook. A real, living algorithm you can interrogate.

<br>

## Live now

<table>
<tr>
<td width="50%" valign="top">

**✦ Signature Algorithms** `9/9`
```
Maximum Contiguous Subarray Sum
Stable Preference Matching
Greedy Shortest Path (Weighted)
Disjoint Set Union + Compression
In-Degree Reduction Topo Sort
Sort-and-Union Min Spanning Tree
Grow-from-Root Min Spanning Tree
Failure-Function Pattern Match
Heuristic Admissible Pathfinding
```

**★ Sliding Window** `10/10`
```
Fixed Window Max / Min
K-Day Rolling Average
Expanding Window with Condition
Shortest Subarray with Sum ≥ X
Longest Valid Subarray
Window with At Most K Distinct
Count Subarrays Meeting Condition
Sliding Anagram Detection
Max Sum in Window of Size K
Smallest Covering Substring
```

**★ Binary Search** `9/10`
```
Classic Sorted Array Search
First and Last Occurrence
Binary Search on Answer Space
Search in Rotated Array
Target in Sorted Matrix
Minimum of Rotated Array
Minimum Capacity Feasibility
Kth Smallest in Sorted Grid
Non-Overlapping Jobs Max Profit
```

</td>
<td width="50%" valign="top">

**★ Graph Visualizers** `10/10`
```
Unique Cycle in Directed Graph
Eliminate Interior Land Masses
BFS Level-Order Tree Scan
Connected Region Size Mapping
Lowest Common Ancestor in Tree
Min BFS Passes to Flip All
Two-Coloring Bipartite Check
Back-Edge Cycle (3-Color DFS)
Grid Word Discovery (Trie+DFS)
Axis-Aligned Rectangle Counting
```

**★ Recursion Collection** `15/15`
```
Overlapping Subproblem Recursion
All Subsets Enumeration
All Orderings Generator
Nested List Weighted Sum
Count Step Combinations
Grid Constraint Solver
Interleaved String Validation
Well-Formed Tag Generation
Keypad Letter Combinations
Deepest Common Ancestor
Card-Draw Bust Probability
Conflict-Free Queen Placement
Measurement Ambiguity Resolver
Binary Tree Shape Enumeration
Recursive Mine Reveal
```

**★ Searching Collection** `9/9`  
**★ Linked List Collection** `2/2`  
**★ Depth-First Search** `7/10`  
**★ Dynamic Programming** `10/19`  

</td>
</tr>
</table>

<br>

## What you actually see

Every step of every visualizer shows you four things simultaneously:

```
┌─────────────────────────────────────────────────────────────────────┐
│  WHAT IT'S LOOKING AT     →   highlighted in the data structure     │
│  WHAT DECISION IT'S MAKING →   the condition being evaluated        │
│  WHY IT MADE THAT DECISION →   the current state that caused it     │
│  WHAT CHANGED              →   the mutation, push, pop, or merge    │
└─────────────────────────────────────────────────────────────────────┘
```

This is not a textbook renderer. Each visualizer is purpose-built for its specific algorithm. The bar chart for max subarray looks nothing like the edge-relaxation panel for Dijkstra's, which looks nothing like the Trie traversal for grid word search.

<br>

## Tech

```
Pure HTML + CSS + Vanilla JavaScript
Zero build tools.  Zero frameworks.  Zero dependencies.
Clone → open index.html → done.
```

| What | How | Why |
|---|---|---|
| Rendering | Canvas + SVG (per visualizer) | Full control, zero overhead |
| Animation | `requestAnimationFrame` | 60fps, pausable, step-controllable |
| Fonts | Space Mono + DM Sans | Precision + readability |
| Hosting | Vercel | Zero-config, instant deploy |
| Setup | Open a file | Literally open a file |

<br>

## Run locally

```bash
git clone https://github.com/yourusername/gbmvisual.git
cd gbmvisual
open index.html
```

That's it. There is no step 4.

If you want a local server (e.g. for CORS):

```bash
python -m http.server 8000
# then: http://localhost:8000
```

<br>

## Structure

```
gbmvisual/
│
├── index.html                        ← The library (50 categories, search, filter)
│
├── 48_GBMfamousalgorithms/          ← ✦ Signature Algorithms
│   ├── 01_kadane.html
│   ├── 02_GBMstable_internships.html
│   ├── 03_Dijkstra_algorithm.html
│   ├── 04_union_find.html
│   ├── 05_GBMtopological_sort.html
│   ├── 06_GBMkruskal.html
│   ├── 07_GBM_Prim.html
│   ├── 08_GBM_knuth_morris_pratt.html
│   └── 09_GBMa_star.html
│
├── GBMgraphs/                        ← Graph Collection (10)
├── GBMsearching/                     ← Searching Collection (9)
├── GBMrecursion/                     ← Recursion Collection (15)
├── GBMlinkedlist/                    ← Linked List Collection (2)
│
├── 01-Two-Pointer/
├── 02-Sliding-Window/                ← 10 live
├── 03-Binary-Search/                 ← 9 live
├── 04-DFS/                           ← 7 live
└── 06-Dynamic-Programming/           ← 10 live
```

<br>

## Contributing a visualizer

**1. Create the file** in the right category folder:
```
02-Sliding-Window/11_your_visualizer.html
```

**2. Every visualizer must have:**
- Step forward / step back / play / reset / speed controls
- The current state of all data structures visible at every frame
- A clear label for what decision is being made at each step
- Color consistency: `#06d6a0` active · `#ffd166` current · `#e63946` rejected
- At least 3 switchable example inputs
- Time and space complexity displayed

**3. Update `index.html`:**
- Find your category section
- Swap `class="card soon"` → `class="card built"` and add the `href`
- Update the live count in the `cat-badge` span (e.g. `1 / 11 live` → `2 / 11 live`)

**4. PR title format:**
```
[Category] Add [Visualizer Name]
```

**Categories most needing contributors right now:**

| Category | Live / Total | Priority |
|---|---|---|
| Breadth-First Search | 0 / 10 | 🔴 High |
| Greedy | 0 / 10 | 🔴 High |
| Stack | 0 / 10 | 🔴 High |
| Heap / Priority Queue | 0 / 10 | 🟡 Medium |
| Dynamic Programming | 10 / 19 | 🟡 Medium |

<br>

## Color system

All visualizers share one canonical color mapping so the same concept is always the same color:

| Color | Hex | Meaning |
|---|---|---|
| 🟢 Teal | `#06d6a0` | Active · selected · correct · live |
| 🟡 Gold | `#ffd166` | Currently examining · frontier |
| 🔵 Blue | `#2196f3` | Visited · queued · processed |
| 🟣 Purple | `#c084fc` | Special collections · highlights |
| 🔴 Red | `#e63946` | Rejected · wrong path · TLE |

<br>

## Progress

| Collection | Live | Total |
|---|---|---|
| ✦ Signature Algorithms | 9 | 9 |
| ★ Graph Visualizers | 10 | 10 |
| ★ Recursion Collection | 15 | 15 |
| ★ Searching Collection | 9 | 9 |
| ★ Linked List Collection | 2 | 2 |
| Sliding Window | 10 | 10 |
| Dynamic Programming | 10 | 19 |
| Binary Search | 9 | 10 |
| Depth-First Search | 7 | 10 |
| Two Pointer | 1 | 11 |
| BFS + 40 more categories | 0 | 370 |
| **Total** | **~82** | **470** |

<br>

## License

MIT — do whatever you want with it. If it helped you understand an algorithm, a ⭐ is the best thanks.

---

<div align="center">

**[gbmvisual.vercel.app](https://gbmvisual.vercel.app)**

*470 problems · 50 categories · built with ♥ for CP*

</div>
