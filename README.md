# 🎯 Zeus Learning (Software Developer) — 3-Day Battle Plan

> Built from: your two PDFs (Recruitment Talk + Development Role Prep Guide) + real interview
> experiences from GeeksforGeeks (2024 on-campus Software Developer, 2025 on-campus, 2024 SDE intern)
> and a LeetCode discussion by a selected 2024 candidate.

---

## 1. Know exactly what you're up against

Zeus Learning is a Mumbai-based e-learning company that builds digital learning products for global
education publishers. Typical fresher package reported ~7.5 LPA (2024, LeetCode discussion — verify
current numbers). The Development-track process:

| Round | Format | What's actually in it (from real reports) |
|---|---|---|
| **1. Online test** (Methyl platform, 75 min–3 hrs) | ~20–25 aptitude MCQs + 8–10 coding questions + CS-fundamentals MCQs | Aptitude is **medium** difficulty and decides whether your coding even matters. Coding: fix syntax/logic errors, **complete a sorting function (merge sort)**, pointer-based output questions, **linked-list loop detection**, **rectangle intersection**. Plus DBMS/OS/DSA MCQs. |
| **2. Pen-and-paper** (1–3 hrs, 20–35 marks) | Written code, no IDE, no phone | Find bugs in pseudocode, **tree depth**, **matrix multiplication logic**, **OOP/inheritance snippets**, **rotate matrix/array 90°**, complete partially-implemented functions, state time/space complexity, dry runs. |
| **3. Technical interview** | 2 interviewers, resume-based | **Project deep-dive** (auth, DB design, scaling), polymorphism **with code**, singly vs doubly linked list, **add 2 numbers without + - * /**, date + X days problem, **search a file in a directory tree (BFS/DFS)**, puzzles (e.g., 10 balls in a rectangle, equal per side), web basics (cookies vs session, tokens, CSS media queries). |
| **4. HR / senior round** | Short talk | Introduce yourself, projects, **why Zeus Learning**, why should we hire you. |

**Sources to read tonight (30 min, non-negotiable):**
- GfG — Software Developer On-Campus 2024: https://www.geeksforgeeks.org/interview-experiences/zeus-learning-interview-experience-for-software-developer-on-campus-2024/
- GfG — Software Developer On-Campus (2025): https://www.geeksforgeeks.org/interview-experiences/zeus-learning-interview-experience-for-software-developer-on-campus/
- GfG — SDE Intern 2024: https://www.geeksforgeeks.org/interview-experiences/zeus-learning-interview-experience-for-software-engineer-intern-2024/
- LeetCode discuss — "Zeus Learning – Software developer 2024 Freshers": https://leetcode.com/discuss/interview-experience/4172686/Zeus-Learning-Software-developer-oror-2024-oror-Freshers/
- Glassdoor Zeus Learning interview Q&A: https://www.glassdoor.co.in/Interview/Zeus-Learning-Pvt-Ltd-Interview-Questions-E253452.htm

**Golden rules from your own PDFs (still true in 3 days):**
- Aptitude speed > depth. If you clear aptitude, coding skills decide the rest.
- Explain the approach, don't memorize. Trace your code by hand.
- Always know time & space complexity of anything you write.
- Know every line of your resume/projects.
- Formats vary by drive — confirm duration/format/cut-offs with your placement cell.

---

## 2. Ground rules for the 3 days

1. **Pick ONE language** (C++ / Java / Python) and write everything in it. Zeus asks to "correct syntax in C/C++ codes" — if your drive uses C/C++, brush up C-style loops/pointers/scanf-printf.
2. **10–12 focused hours/day.** 50 min work + 10 min break cycles.
3. **Solve on paper daily** (Days 1–3 evening): pen-and-paper Round 2 is where most people fail.
4. **Don't watch passively.** Watch at 1.25–1.5x, pause, solve before the solution.
5. Phone on Do Not Disturb; aptitude practice always **timed**.
6. Keep one notebook as your **cheat sheet** — every pattern, formula, and mistake goes there. You'll revise only this on Day 3 night and the morning of the test.

---

## 3. Tonight (Day 0) — 1.5 hours of setup

- [ ] Confirm drive details with the placement cell: platform, duration, number of coding questions, allowed language(s).
- [ ] Make a 1-page resume. Remove anything you can't defend.
- [ ] Write your 60-second intro (name → degree → strongest project → what you're looking for).
- [ ] Create/verify LeetCode account; bookmark the problem list in Section 7.
- [ ] Read the 4 interview-experience links above.
- [ ] Write these on your cheat sheet now (they were **actually asked**):
  - Linked list cycle detection (Floyd's) · Rectangle overlap logic · Merge sort from memory ·
  - Rotate matrix 90° · Add two ints without operators · File-in-directory BFS/DFS ·
  - Add X days to a DD/MM/YYYY date · Tree depth · 10-balls-in-rectangle puzzle

---

## 4. DAY 1 — Aptitude + Logical Reasoning + Output Prediction

### Morning block (4 hrs) — Quantitative aptitude
Topics (exactly your PDF's list): **percentages, profit & loss, ratio & proportion, averages, time-speed-distance, time & work, number systems, data interpretation.**

- 1.5 hr: watch shortcuts — one playlist from Section 8, only these topics.
- 2.5 hrs: **timed drilling on IndiaBIX** (https://www.indiabix.com) — 60–80 questions, ~1 min each.
- Learn these cold: successive % change formula, CP/SP/MP relations, avg-speed = 2xy/(x+y), unitary method for work, LCM trick for cycles, calendar/odd-days basics, Venn-based data interpretation.

### Afternoon block (2.5 hrs) — Logical reasoning
- **Number/alphabet series, coding-decoding, blood relations (draw the tree!), directions (draw the compass!), arrangements, syllogisms.**
- 30–40 IndiaBIX reasoning questions, timed.
- Puzzles from your talk deck (they recycle these in interviews): 3-digit lock (042), socks in the dark (3 / 12), three switches & bulbs (heat trick), 5L-3L jugs (4L), two ropes 45 min, painted 4×4×4 cube (8/24/24/8), three mislabelled boxes, 100 bananas (day 1 = 8), brick = 2 kg.

### Evening block (3 hrs) — Programming fundamentals & output prediction
This is Round 1's hidden differentiator. Zeus asks **pointer and output-prediction questions**:
- C/C++: operator precedence, integer division, `i++` vs `++i`, short-circuit evaluation, `char` arithmetic, arrays decay to pointers, string literals, `static`, scope/shadowing, pass-by-value vs reference, default args, overflow.
- Drill: 20–30 "predict the output" questions from GeeksforGeeks C Output / C++ Output sections + fix-the-bug snippets.

### Night block (1.5–2 hrs) — LeetCode Set 1 (easy warm-up, ~25 min each)
Write on LeetCode, then **hand-trace one of them on paper**.

| # | Problem |
|---|---|
| 344 | Reverse String — [leetcode.com/problems/reverse-string](https://leetcode.com/problems/reverse-string/) |
| 125 | Valid Palindrome — [leetcode.com/problems/valid-palindrome](https://leetcode.com/problems/valid-palindrome/) |
| 217 | Contains Duplicate |
| 387 | First Unique Character in a String |
| 169 | Majority Element |
| 283 | Move Zeroes |
| 268 | Missing Number |
| 136 | Single Number |
| 66 | Plus One |
| 704 | Binary Search |

---

## 5. DAY 2 — DSA core + OOP + the "actually asked" problems

### Morning block (4 hrs) — Arrays / strings / hashing / sorting / binary search
Watch 1 hr of a DSA one-shot (Section 8) covering these, then solve ~10 problems:

| # | Problem | Why |
|---|---|---|
| 1 | Two Sum | classic hashmap |
| 20 | Valid Parentheses | stack |
| 121 | Best Time to Buy and Sell Stock | one-pass |
| 53 | Maximum Subarray | Kadane's |
| 242 | Valid Anagram | freq count |
| 14 | Longest Common Prefix | strings |
| 88 | Merge Sorted Array | two-pointer |
| 189 | Rotate Array | asked (rotate!) |
| 287 | Find the Duplicate Number | Floyd's variant |
| 26 | Remove Duplicates from Sorted Array | in-place |
| 724 | Find Pivot Index | prefix sums |

**Then write merge sort BY HAND on paper** (Zeus asked candidates to *complete a merge sort function*). Also write binary search by hand — off-by-one errors are the #1 paper-test killer.

### Afternoon block (3 hrs) — Linked lists + trees + recursion
| # | Problem | Why |
|---|---|---|
| 206 | Reverse Linked List | #1 most-asked |
| 141 | Linked List Cycle | **directly asked in Zeus online test** |
| 876 | Middle of the Linked List | slow/fast pointers |
| 21 | Merge Two Sorted Lists | recursion + pointers |
| 83 | Remove Duplicates from Sorted List | easy pointer practice |
| 94 | Binary Tree Inorder Traversal | traversal (write all 3 orders by hand) |
| 104 | Maximum Depth of Binary Tree | **asked in pen-paper round** |
| 226 | Invert Binary Tree | recursion |
| 102 | Level Order Traversal | BFS queue |
| 100 | Same Tree | recursion |

Also learn: singly vs **doubly** linked list pros/cons (interview asked), print leaf nodes, count nodes.

### Evening block (2.5 hrs) — OOP (watch + handwrite)
- Watch Apna College **OOPs in One Shot** (link in Section 8) at 1.5x.
- Handwrite: a `Shape` base class → `Circle`, `Rectangle` with overridden `area()`; an interface `Payment` → `CardPayment`, `UpiPayment`.
- Memorize with one-line real examples: 4 pillars; **overloading vs overriding**; **interface vs abstract class**; constructor types; `static`; access modifiers; composition vs inheritance; Java collections (ArrayList/HashMap) basic methods.
- Practice "complete the partially implemented class" drills — Zeus Round 2 explicitly does this.

### Night block (1.5 hrs) — The Zeus-special five (write ALL on paper)
These exact problems appeared in real Zeus rounds:
1. **836 Rectangle Overlap** — overlap iff `rect1.left < rect2.right && rect2.left < rect1.right && rect1.top > rect2.bottom && rect2.top > rect1.bottom` (tune for coordinate system).
2. **48 Rotate Image** (rotate matrix 90°) — transpose, then reverse rows.
3. **371 Sum of Two Integers** — `a + b = a XOR b + (a AND b) << 1` loop (or explain the idea if bit math is shaky).
4. **Date + X days → new DD/MM/YYYY** — write with a days-in-month lookup + leap year rule.
5. **find(file, folder)** using given `getFolder(folder)` and `getFiles(folder)` — BFS with a queue (or recursive DFS). The 2024 selected candidate solved exactly this in the interview.

---

## 6. DAY 3 — CS fundamentals + full mock + interview rehearsal

### Morning block (3 hrs) — DBMS + OS + Networks + Web
- **DBMS/SQL (1.5 hr):** primary/foreign key, INNER vs LEFT JOIN, GROUP BY + aggregates, WHERE vs HAVING, normalization (1NF/2NF/3NF one-liners), basic SELECT/ORDER BY. **Handwrite 10 queries.** Watch: Gate Smashers "Complete SQL Interview Questions in One Shot | Placement Revision".
- **OS (45 min):** process vs thread, scheduling types, deadlock (4 conditions), paging/segmentation, virtual memory, mutex vs semaphore. Watch: Anuj Bhaiya OS in One Shot or Gate Smashers OS in 100 minutes.
- **Networks (30 min):** HTTP vs HTTPS, TCP 3-way handshake, request-response lifecycle, DNS, common HTTP methods & status codes, what is an API.
- **Web (15 min):** cookies vs session, tokens/JWT, DOM & events, CSS media queries (an SDE-intern candidate was asked to *write one*).

### Afternoon block A (2.5 hrs) — **Full Round-2 simulation on paper**
One sitting, timed, no IDE/phone, answers straight on paper, neat + labelled:
1. Fix 5 bugs in a buggy merge-sort function (ask a friend to plant bugs, or copy your own morning code and corrupt it).
2. Tree depth + print leaf nodes (write both).
3. Matrix multiplication logic (3 nested loops + dimension check).
4. Rotate a matrix 90° in-place.
5. Complete a partially implemented `Student` class with an inherited `GradStudent` (constructor + overridden method).
6. Rectangle overlap function.
7. Reverse a linked list (iterative + recursive).
8. First non-repeating character in a string, O(n).
9. FizzBuzz + swap two numbers without a temp variable.
10. State Big-O for every solution above.

Score yourself: dry-run each on a sample input, then an empty/edge input, exactly like the guide says.

### Afternoon block B (1 hr) — Aptitude mini-mock
25 mixed IndiaBIX questions in 35 minutes, twice if time permits. Accuracy > 80% or review tonight.

### Evening block (2.5 hrs) — Interview rehearsal (out loud, record yourself)
- **60-second intro.**
- **Project story ×2** (use STAR): problem → stack → architecture diagram (draw it) → *your* contribution → hardest bug + how you debugged → what you'd improve. If web: know your auth flow and DB schema cold — both were probed in real Zeus interviews.
- **Rapid-fire answers (actually asked at Zeus):** explain polymorphism with code · singly vs doubly LL · add 2 ints without operators · cookies vs session · tokens · scaling a web app · why BFS/DFS for file search · SQL join types.
- **Puzzles:** re-solve the Day 1 puzzle list + 10-balls-in-a-rectangle (hint: 3-3-2-2 = 10, or arrange with shared corner balls — explain reasoning aloud; approach matters more than the answer).
- **Why Zeus Learning:** Mumbai-based e-learning company building interactive courseware/simulations/assessments for global education publishers — say *that*, plus why education tech excites you and (if true) product + learning culture. Skim zeuslearning.com for 10 minutes.
- Prepare **2 questions to ask them** (e.g., "What does a fresher's first 6 months look like?", "How do devs and QA collaborate on a feature?").

### Night (1 hr)
- Revise ONLY your notebook: complexity table, OOP one-liners, SQL joins, mistakes log.
- Sleep 7+ hours. No new topics after dinner.

---

## 7. LeetCode master list (keep this open all 3 days)

**Must-do (25):** 1, 20, 121, 53, 242, 14, 88, 189, 287, 26, 724, 344, 125, 217, 387, 169, 283, 268, 704, 206, 141, 876, 94, 104, 48
**Zeus-specials (5):** 836, 371, 102, 226, 21
**Stretch if ahead of schedule:** 136, 66, 100, 83, 278 (First Bad Version), 35 (Search Insert Position), 412 (Fizz Buzz), 151 (Reverse Words in a String), 223 (Rectangle Area)

Format: `leetcode.com/problems/<slug>/` — e.g. [Two Sum](https://leetcode.com/problems/two-sum/), [Rectangle Overlap](https://leetcode.com/problems/rectangle-overlap/), [Sum of Two Integers](https://leetcode.com/problems/sum-of-two-integers/), [Linked List Cycle](https://leetcode.com/problems/linked-list-cycle/), [Rotate Image](https://leetcode.com/problems/rotate-image/).

Target: **~30 problems solved + every one of them re-traced on paper.** Speed of writing correct code on paper > quantity.

---

## 8. YouTube resources (links verified)

| Purpose | Resource | Link |
|---|---|---|
| DSA (pseudocode, placement-focused) | **Striver's A2Z DSA Course playlist** — pick: patterns, sorting (merge!), arrays, hashing, binary search, LL, trees | https://www.youtube.com/playlist?list=PLgUwDviBIf0oF6QL8m22w1hIDC1vJ_BHz |
| DSA (C++/Java-friendly alternative) | Apna College — DSA series by Shradha Khapra | https://www.youtube.com/watch?v=1yrh60og6qc |
| OOP one shot | **Apna College — OOPs Tutorial in One Shot (C++, for placement interviews)** | https://www.youtube.com/watch?v=mlIUKyZIUUU |
| OS quick revision | **Anuj Bhaiya — Operating System in One Shot** | https://www.youtube.com/watch?v=8XBtAjKwCm4 |
| OS ultra-quick | Gate Smashers — "Operating System OS in 100 Minutes \| Complete Placement Revision" | https://www.youtube.com/watch?v=KlwNyagHWuk |
| OS + SQL interview one-shots | Gate Smashers — search their channel for "**Complete SQL Interview Questions in One Shot \| Placement Revision**" and "Complete OS Interview Question in One Shot" | Channel: https://www.youtube.com/channel/UCJihyK0A38SZ6SdJirEdIOw |
| SQL basics | "Full SQL Crash Course — Learn SQL in 90 Minutes" | https://www.youtube.com/watch?v=7cIG41gjHB4 |
| Quant aptitude playlist | Quantitative Aptitude Tutorials (placement tests) | https://www.youtube.com/playlist?list=PLpyc33gOcbVA4qXMoQ5vmhefTruk5t9lt |
| Logical reasoning playlist | Logical Reasoning Tutorial (placement tests) | https://www.youtube.com/playlist?list=PLpyc33gOcbVADMKqylI__O_O_RMeHTyNK |
| Aptitude (alt) | Code Step By Step — Aptitude Preparation for Campus Placement | https://www.youtube.com/playlist?list=PL8p2I9GklV454LdGfDOw0KkNazKuA-6B2 |
| Output prediction | GeeksforGeeks "C Output" / "C++ Output" question sets (search those exact phrases) | https://www.geeksforgeeks.org |

Practice sites: **IndiaBIX** (aptitude + reasoning) https://www.indiabix.com · **GeeksforGeeks quizzes** for CS subjects.

---

## 9. Cheat sheets to memorize (write these in your notebook tonight)

### Complexity table
| Structure/Algorithm | Time |
|---|---|
| Array access / HashMap ops (avg) | O(1) |
| Binary search | O(log n) |
| Merge/Heap sort | O(n log n) |
| Bubble/Insertion/Selection | O(n²) |
| Reverse LL / tree traversals | O(n) |
| BFS/DFS on graph/tree | O(V + E) |

### OOP one-liners
- **Encapsulation** = private data + public methods (getter/setter). **Abstraction** = hide implementation, show behaviour (interface/abstract). **Inheritance** = reuse via parent class. **Polymorphism** = one interface, many forms (overload = compile-time, override = runtime via `virtual`/`@Override`).
- Interface: no state, multiple inheritance of type. Abstract class: can hold state + constructors, single inheritance.
- Overloading: same name, different params, same class. Overriding: same signature, subclass replaces parent behaviour.

### SQL skeleton
`SELECT cols FROM t JOIN t2 ON k WHERE filter GROUP BY g HAVING agg ORDER BY o LIMIT n;`
- PK = unique + not null; FK = references another table's PK. INNER = only matches; LEFT = all left rows + matches (NULL otherwise).

### OS / CN must-knows
- Process = isolated address space; Thread = shared memory within a process. Deadlock needs: mutual exclusion, hold & wait, no preemption, circular wait.
- HTTP = plain text, port 80; HTTPS = TLS-encrypted, port 443. TCP: SYN → SYN-ACK → ACK. GET/POST/PUT/DELETE; 200/301/404/500.
- Cookie = client-side storage sent with requests; Session = server-side state identified by cookie; Token (JWT) = signed stateless credential.

---

## 10. Final checklist (print this)

- [ ] Aptitude: 100+ timed questions done across 3 days
- [ ] Merge sort, binary search, reverse LL, tree traversals written **from memory on paper**
- [ ] The Zeus-special five solved on paper (836, 48, 371, date, file-search BFS)
- [ ] OOP: 4 pillars + overload/override + interface/abstract, with handwritten example
- [ ] 10 SQL queries handwritten; joins + keys solid
- [ ] Project: 2-minute architecture story + hardest bug + one improvement
- [ ] "Why Zeus Learning" 30-second answer
- [ ] Two questions to ask the panel
- [ ] Notebook revised; 7 hours sleep before the drive

**Mindset (from the selected candidates):** they explain their approach out loud, start with a correct brute-force solution then optimize, and stay calm when stuck. Aptitude accuracy got them to the interview; clarity and honesty got them the offer. Good luck! 🚀
