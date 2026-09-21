# 🧩 DSA Patterns Cheat Sheet

A curated, pattern-wise collection of DSA problems for structured interview prep. Each pattern groups problems that share a common technique — solve them in order to build intuition before jumping into random practice.

> 💡 **How to use this sheet:** Pick one pattern at a time. Solve the "easy" problems first to internalize the pattern, then move to "medium" and "hard"/"Problem Challenge" problems to stress-test it.

---

## Table of Contents

1. [Two Pointers](#1-two-pointers)
2. [Fast & Slow Pointers](#2-fast--slow-pointers)
3. [Sliding Window](#3-sliding-window)
4. [Kadane's Pattern](#kadanes-pattern)
5. [Prefix Sum](#prefix-sum)
6. [Merge Intervals](#4-merge-intervals)
7. [In-place Reversal of a LinkedList](#6-in-place-reversal-of-a-linkedlist)
8. [Stack](#7-stack)
9. [Hash Maps](#9-hash-maps)
10. [Binary Search](#10-binary-search)
11. [Heap Pattern](#heap-pattern)
12. [Recursion & Backtracking](#recursion-and-backtracking-pattern)
13. [Tree Pattern](#tree-pattern)
14. [Graphs](#graphs)
15. [Dynamic Programming](#dp-dynamic-programming)

---

## 1. Two Pointers

| Problem | Difficulty | Link |
|---|---|---|
| Pair with Target Sum | Easy | [LeetCode](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted/description/) |
| Rearrange 0s and 1s | Easy | [GfG](https://www.geeksforgeeks.org/problems/segregate-0s-and-1s5106/1) |
| Remove Duplicates | Easy | [LeetCode I](https://leetcode.com/problems/remove-duplicates-from-sorted-list/) · [LeetCode II](https://leetcode.com/problems/remove-duplicates-from-sorted-array/description/) · [LeetCode III](https://leetcode.com/problems/remove-duplicates-from-sorted-array-ii/) |
| Squaring a Sorted Array | Easy | [LeetCode](https://leetcode.com/problems/squares-of-a-sorted-array/) |
| Triplet Sum to Zero | Medium | [LeetCode](https://leetcode.com/problems/3sum/) |
| Triplet Sum Close to Target | Medium | [LeetCode](https://leetcode.com/problems/3sum-closest/) |
| Triplets with Smaller Sum | Medium | [GfG](https://www.geeksforgeeks.org/problems/count-triplets-with-sum-smaller-than-x5549/1) |
| Subarrays with Product Less than a Target | Medium | [LeetCode](https://leetcode.com/problems/subarray-product-less-than-k/) |
| Dutch National Flag Problem | Medium | [LeetCode](https://leetcode.com/problems/sort-colors/description/) |
| **Challenge 1:** Quadruple Sum to Target | Medium | [LeetCode](https://leetcode.com/problems/4sum/) |
| **Challenge 2:** Comparing Strings with Backspaces | Medium | [LeetCode](https://leetcode.com/problems/backspace-string-compare/) |
| **Challenge 3:** Minimum Window Sort | Medium | [LeetCode](https://leetcode.com/problems/shortest-unsorted-continuous-subarray/) · [Reference](https://www.ideserve.co.in/learn/minimum-length-subarray-sorting-which-results-in-sorted-array) |

## 2. Fast & Slow Pointers

| Problem | Difficulty | Link |
|---|---|---|
| LinkedList Cycle | Easy | [LeetCode](https://leetcode.com/problems/linked-list-cycle/) |
| Start of LinkedList Cycle | Medium | [LeetCode](https://leetcode.com/problems/linked-list-cycle-ii/) |
| Happy Number | Medium | [LeetCode](https://leetcode.com/problems/happy-number/) |
| Find Duplicate Number | Medium | [LeetCode](https://leetcode.com/problems/find-the-duplicate-number/description/) |
| Middle of the LinkedList | Easy | [LeetCode](https://leetcode.com/problems/middle-of-the-linked-list/) |
| **Challenge 1:** Palindrome LinkedList | Medium | [LeetCode](https://leetcode.com/problems/palindrome-linked-list/) |
| **Challenge 2:** Rearrange a LinkedList | Medium | [LeetCode](https://leetcode.com/problems/reorder-list/) |
| **Challenge 3:** Cycle in a Circular Array | Hard | [LeetCode](https://leetcode.com/problems/circular-array-loop/) |

## 3. Sliding Window

| Problem | Difficulty | Link |
|---|---|---|
| Maximum Sum Subarray of Size K | Easy | [GfG](https://www.geeksforgeeks.org/problems/max-sum-subarray-of-size-k5313/1) |
| Smallest Subarray with a Given Sum | Easy | [LeetCode](https://leetcode.com/problems/minimum-size-subarray-sum/) |
| Longest Substring with K Distinct Characters | Medium | [GfG](https://www.geeksforgeeks.org/problems/longest-k-unique-characters-substring0853/1) |
| Fruits into Baskets | Medium | [LeetCode](https://leetcode.com/problems/fruit-into-baskets/) |
| No-repeat Substring | Hard | [LeetCode](https://leetcode.com/problems/longest-substring-without-repeating-characters/) |
| Longest Substring with Same Letters after Replacement | Hard | [LeetCode](https://leetcode.com/problems/longest-repeating-character-replacement/) |
| Longest Subarray with Ones after Replacement | Hard | [LeetCode](https://leetcode.com/problems/max-consecutive-ones-iii/) |
| Minimum Size Subarray Sum | — | [LeetCode](https://leetcode.com/problems/minimum-size-subarray-sum/) |
| Minimum Window Substring | Hard | [LeetCode](https://leetcode.com/problems/minimum-window-substring/description/?envType=study-plan-v2&envId=top-interview-150) |
| **Challenge 1:** Permutation in a String | Hard | [LeetCode](https://leetcode.com/problems/permutation-in-string/) |
| **Challenge 2:** String Anagrams | Hard | [LeetCode](https://leetcode.com/problems/find-all-anagrams-in-a-string/) |
| **Challenge 4:** Words Concatenation | Hard | [LeetCode](https://leetcode.com/problems/substring-with-concatenation-of-all-words/) |

### Kadane's Pattern

| Problem | Link |
|---|---|
| Maximum Subarray Sum | [LeetCode](https://leetcode.com/problems/maximum-subarray/) |
| Minimum Subarray Sum | [GfG](https://www.geeksforgeeks.org/problems/smallest-sum-contiguous-subarray/1) |
| Maximum Product Subarray | [LeetCode](https://leetcode.com/problems/maximum-product-subarray/) |
| Maximum Subarray Sum with One Deletion | [LeetCode](https://leetcode.com/problems/maximum-subarray-sum-with-one-deletion/description/) |
| Maximum Absolute Sum of Any Subarray | [LeetCode](https://leetcode.com/problems/maximum-absolute-sum-of-any-subarray/) |
| Maximum Sum in Circular Array (variant) | [LeetCode](https://leetcode.com/problems/maximum-sum-circular-subarray/) |

### Prefix Sum

| Problem | Difficulty | Link |
|---|---|---|
| Subarray Sum Equals K | Easy | [LeetCode](https://leetcode.com/problems/subarray-sum-equals-k/description/) |
| Find Pivot Index | Easy | [LeetCode](https://leetcode.com/problems/find-pivot-index/description/) |
| Subarray Sums Divisible By K | Medium | [LeetCode](https://leetcode.com/problems/subarray-sums-divisible-by-k/description/) |
| Contiguous Array | Medium | [LeetCode](https://leetcode.com/problems/contiguous-array/description/) |
| **Challenge:** Shortest Subarray With Sum at Least K | Hard | [LeetCode](https://leetcode.com/problems/shortest-subarray-with-sum-at-least-k/description/) |
| **Challenge:** Count Range Sum | Hard | [LeetCode](https://leetcode.com/problems/count-of-range-sum/description/) |

## 4. Merge Intervals

| Problem | Difficulty | Link |
|---|---|---|
| Merge Intervals | Medium | [LeetCode](https://leetcode.com/problems/merge-intervals/description/) |
| Insert Interval | Medium | [LeetCode](https://leetcode.com/problems/insert-interval/) |
| Intervals Intersection | Medium | [LeetCode](https://leetcode.com/problems/interval-list-intersections/description/) |
| Overlapping Intervals | — | [GfG](https://www.geeksforgeeks.org/check-if-any-two-intervals-overlap-among-a-given-set-of-intervals/) |
| **Challenge 1:** Minimum Meeting Rooms | Hard | [GfG](https://www.geeksforgeeks.org/problems/attend-all-meetings-ii/1) |
| **Challenge 2:** Maximum CPU Load | Hard | [GfG](https://www.geeksforgeeks.org/maximum-cpu-load-from-the-given-list-of-jobs/) |
| **Challenge 3:** Employee Free Time | Hard | [CoderTrain](https://www.codertrain.co/employee-free-time) |

## 6. In-place Reversal of a LinkedList

| Problem | Difficulty | Link |
|---|---|---|
| Reverse a LinkedList | Easy | [LeetCode](https://leetcode.com/problems/reverse-linked-list/) |
| Reverse a Sub-list | Medium | [LeetCode](https://leetcode.com/problems/reverse-linked-list-ii/) |
| Reverse List in Pairs | Medium | [LeetCode](https://leetcode.com/problems/swap-nodes-in-pairs/description/) |
| Reverse Every K-element Sub-list | Hard | [LeetCode](https://leetcode.com/problems/reverse-nodes-in-k-group/) |
| **Challenge 1:** Reverse Nodes in Even Length Groups | Hard | [LeetCode](https://leetcode.com/problems/reverse-nodes-in-even-length-groups/description/) |
| **Challenge 2:** Rotate a LinkedList | Medium | [LeetCode](https://leetcode.com/problems/rotate-list/) |

## 7. Stack

| Problem | Difficulty | Link |
|---|---|---|
| Remove Adjacent Duplicates | — | [LeetCode](https://leetcode.com/problems/remove-all-adjacent-duplicates-in-string/description/) |
| Balanced Parentheses | — | [LeetCode](https://leetcode.com/problems/valid-parentheses/description/) |
| Next Greater Element | Easy | [LeetCode](https://leetcode.com/problems/next-greater-element-ii/description/) |
| Daily Temperatures | Easy | [LeetCode](https://leetcode.com/problems/daily-temperatures/) |
| Remove Nodes From Linked List | Easy | [LeetCode](https://leetcode.com/problems/remove-nodes-from-linked-list/) |
| Remove All Adjacent Duplicates in String II | Medium | [LeetCode](https://leetcode.com/problems/remove-all-adjacent-duplicates-in-string-ii/) |
| Simplify Path | Challenge | [LeetCode](https://leetcode.com/problems/simplify-path/) |
| Remove K Digits | Hard / Challenge | [LeetCode](https://leetcode.com/problems/remove-k-digits/) |

## 9. Hash Maps

| Problem | Difficulty | Link |
|---|---|---|
| First Non-repeating Character | Easy | [LeetCode](https://leetcode.com/problems/first-unique-character-in-a-string/) |
| Maximum Number of Balloons | Easy | [LeetCode](https://leetcode.com/problems/maximum-number-of-balloons/) |
| Longest Palindrome | Easy | [LeetCode](https://leetcode.com/problems/longest-palindrome/) |
| Ransom Note | Easy | [LeetCode](https://leetcode.com/problems/ransom-note/) |

## 10. Binary Search

| Problem | Link |
|---|---|
| Binary Search (basic) | [LeetCode](https://leetcode.com/problems/binary-search/) |
| Upper Bound / Ceiling | [GfG](https://www.geeksforgeeks.org/problems/ceil-in-a-sorted-array/1) |
| First and Last Position | [LeetCode](https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array/) |
| Count Number of Occurrences | [GfG](https://www.geeksforgeeks.org/problems/number-of-occurrence2259/1) |
| Search in Infinite Sorted Array | [GfG](https://www.geeksforgeeks.org/find-position-element-sorted-array-infinite-numbers/) |
| Peak Index in Mountain Array | [LeetCode](https://leetcode.com/problems/peak-index-in-a-mountain-array/) |
| Find Peak Element | [LeetCode](https://leetcode.com/problems/find-peak-element/) |
| Find Minimum in Rotated Sorted Array | [LeetCode](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/) |
| Number of Rotations in Sorted Array | [GfG](https://www.geeksforgeeks.org/problems/rotation4723/1) |
| Search in Rotated Sorted Array | [LeetCode](https://leetcode.com/problems/search-in-rotated-sorted-array/description/) |
| Koko Eating Bananas | [LeetCode](https://leetcode.com/problems/koko-eating-bananas/) |
| Min Days to Make M Bouquets | [LeetCode](https://leetcode.com/problems/minimum-number-of-days-to-make-m-bouquets/) |
| Aggressive Cows | [GfG](https://www.geeksforgeeks.org/problems/aggressive-cows/1) |
| H-Index II | [LeetCode](https://leetcode.com/problems/h-index-ii/description/) |
| Max Candies Allocated to K Children | [LeetCode](https://leetcode.com/problems/maximum-candies-allocated-to-k-children/description/) |
| Capacity to Ship Packages within D Days | [LeetCode](https://leetcode.com/problems/capacity-to-ship-packages-within-d-days/description/) |
| Book Allocation Problem | [GfG](https://www.geeksforgeeks.org/problems/allocate-minimum-number-of-pages0937/1) |
| Split Array Largest Sum | [LeetCode](https://leetcode.com/problems/split-array-largest-sum/description/) |
| Search a 2D Matrix | [LeetCode](https://leetcode.com/problems/search-a-2d-matrix/) |
| Search a 2D Matrix II (Hard) | [LeetCode](https://leetcode.com/problems/search-a-2d-matrix-ii/description/) |
| Kth Smallest in Sorted Matrix | [LeetCode](https://leetcode.com/problems/kth-smallest-element-in-a-sorted-matrix/description/) |
| Kth Smallest in Multiplication Table | [LeetCode](https://leetcode.com/problems/kth-smallest-number-in-multiplication-table/description/) |
| Median of Two Sorted Arrays | [LeetCode](https://leetcode.com/problems/median-of-two-sorted-arrays/) |

### Heap Pattern

| Problem | Link |
|---|---|
| Kth Smallest Element | [GfG](https://www.geeksforgeeks.org/problems/kth-smallest-element5635/1) |
| Kth Largest Element in an Array | [LeetCode](https://leetcode.com/problems/kth-largest-element-in-an-array/description/) |
| Top K Frequent Elements | [LeetCode](https://leetcode.com/problems/top-k-frequent-elements/description/) |
| Top K Frequent Words | [LeetCode](https://leetcode.com/problems/top-k-frequent-words/description/) |
| K Closest Points to Origin | [LeetCode](https://leetcode.com/problems/k-closest-points-to-origin/description/) |
| Find K Closest Elements | [LeetCode](https://leetcode.com/problems/find-k-closest-elements/description/) |
| Kth Weakest Row in a Matrix | [LeetCode](https://leetcode.com/problems/the-k-weakest-rows-in-a-matrix/description/) |
| **Heap as Pointer** — Merge K Sorted Arrays | [GfG](https://www.geeksforgeeks.org/problems/merge-k-sorted-arrays/1) |
| Kth Smallest in Sorted Matrix | [LeetCode](https://leetcode.com/problems/kth-smallest-element-in-a-sorted-matrix/description/) |
| **Greedy + Heap** — Last Stone Weight | [LeetCode](https://leetcode.com/problems/last-stone-weight/description/) |
| CPU Task Scheduler | [LeetCode](https://leetcode.com/problems/task-scheduler/description/) |
| Reorganize String | [LeetCode](https://leetcode.com/problems/reorganize-string/) |
| Minimum Number of Refueling Stops | [LeetCode](https://leetcode.com/problems/minimum-number-of-refueling-stops/description/) |
| IPO | [LeetCode](https://leetcode.com/problems/ipo/description/) |
| Course Schedule III | [LeetCode](https://leetcode.com/problems/course-schedule-iii/description/) |
| **Two Heaps** — Find Median from Data Stream | [LeetCode](https://leetcode.com/problems/find-median-from-data-stream/description/) |
| Sliding Window Median (Hard) | [LeetCode](https://leetcode.com/problems/sliding-window-median/description/) |

## Recursion and Backtracking Pattern

| Problem | Link | Video |
|---|---|---|
| Fibonacci | [LeetCode](https://leetcode.com/problems/fibonacci-number/description/) | [YT](https://www.youtube.com/watch?v=j4wjZqzhMqc&t) |
| Check if String is Palindrome | [GfG](https://www.geeksforgeeks.org/problems/palindrome-string0817/1) | [YT](https://www.youtube.com/watch?v=j4wjZqzhMqc&t) |
| Check if Array is Sorted | [GfG](https://www.geeksforgeeks.org/problems/check-if-an-array-is-sorted0701/1) | [YT](https://www.youtube.com/watch?v=-gC-QEdpvO4) |
| Sum of Digits of a Number | [GfG](https://www.geeksforgeeks.org/problems/sum-of-digits1742/1) | [YT](https://www.youtube.com/watch?v=-gC-QEdpvO4) |
| Remove Occurrences of a Character in String | [GfG](https://www.geeksforgeeks.org/problems/remove-all-occurrences-of-a-character-in-a-string/1) | [YT](https://www.youtube.com/watch?v=-gC-QEdpvO4) |
| Generate Parentheses | [LeetCode](https://leetcode.com/problems/generate-parentheses/description/) | — |
| Letter Combinations of Phone Number | [LeetCode](https://leetcode.com/problems/letter-combinations-of-a-phone-number/description/) | [YT](https://www.youtube.com/watch?v=IKfIT6uFOcs) |
| Permutations | [LeetCode](https://leetcode.com/problems/permutations/description/) | — |
| Combination Sum | [LeetCode](https://leetcode.com/problems/combination-sum/description/) | — |
| Palindrome Partitioning | [LeetCode](https://leetcode.com/problems/palindrome-partitioning/description/) | — |

## Tree Pattern

**Traversal**

| Problem | Link |
|---|---|
| Inorder Traversal | [LeetCode](https://leetcode.com/problems/binary-tree-inorder-traversal/description/) |
| Preorder Traversal | [LeetCode](https://leetcode.com/problems/binary-tree-preorder-traversal/description/) |
| Postorder Traversal | [LeetCode](https://leetcode.com/problems/binary-tree-postorder-traversal/description/) |
| Level Order *(homework)* | [LeetCode](https://leetcode.com/problems/binary-tree-level-order-traversal/description/) |
| ZigZag Level Order | [LeetCode](https://leetcode.com/problems/binary-tree-zigzag-level-order-traversal/description/) |
| Level Order II | [LeetCode](https://leetcode.com/problems/binary-tree-level-order-traversal-ii/description/) |

**Mirror & Symmetry** *(homework)*

| Problem | Link |
|---|---|
| Invert Tree | [LeetCode](https://leetcode.com/problems/invert-binary-tree/description/) |
| Symmetric Tree | [LeetCode](https://leetcode.com/problems/symmetric-tree/description/) |
| Same Tree | [LeetCode](https://leetcode.com/problems/same-tree/description/) |
| Subtree of Another Tree | [LeetCode](https://leetcode.com/problems/subtree-of-another-tree/description/) |
| Flip Equivalent Tree | [LeetCode](https://leetcode.com/problems/flip-equivalent-binary-trees/description/) |

**Search**

| Problem | Link |
|---|---|
| LCA of Binary Tree | [LeetCode](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree/description/) |
| Search in a Binary Search Tree | [LeetCode](https://leetcode.com/problems/search-in-a-binary-search-tree/) |
| LCA of BST | [LeetCode](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-search-tree/description/) |
| LCA of Deepest Leaves | [LeetCode](https://leetcode.com/problems/lowest-common-ancestor-of-deepest-leaves/description/) |
| Two Sum IV — Input is a BST | [LeetCode](https://leetcode.com/problems/two-sum-iv-input-is-a-bst/description/) |
| Kth Smallest Element in BST | [LeetCode](https://leetcode.com/problems/kth-smallest-element-in-a-bst/description/) |

**Validation**

| Problem | Link |
|---|---|
| Minimum Depth of Binary Tree | [LeetCode](https://leetcode.com/problems/minimum-depth-of-binary-tree/description/) |
| Maximum Depth of Binary Tree | [LeetCode](https://leetcode.com/problems/maximum-depth-of-binary-tree/description/) |
| Balanced Binary Tree | [LeetCode](https://leetcode.com/problems/balanced-binary-tree/description/) |
| Diameter of Binary Tree | [LeetCode](https://leetcode.com/problems/diameter-of-binary-tree/description/) |
| Check Completeness of Binary Tree | [LeetCode](https://leetcode.com/problems/check-completeness-of-a-binary-tree/description/) |
| Validate BST | [LeetCode](https://leetcode.com/problems/validate-binary-search-tree/description/) |
| Recover BST | [LeetCode](https://leetcode.com/problems/recover-binary-search-tree/description/) |

**Path Sum**

| Problem | Link |
|---|---|
| Path Sum | [LeetCode](https://leetcode.com/problems/path-sum/description/) |
| Path Sum II | [LeetCode](https://leetcode.com/problems/path-sum-ii/) |
| Sum of Root to Leaf Numbers | [LeetCode](https://leetcode.com/problems/sum-root-to-leaf-numbers/description/) |
| Binary Tree Maximum Path Sum | [LeetCode](https://leetcode.com/problems/binary-tree-maximum-path-sum/description/) |

**Construction**

| Problem | Link |
|---|---|
| Construct Tree from Preorder + Inorder | [LeetCode](https://leetcode.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/description/) |
| Construct Tree from Postorder + Inorder | [LeetCode](https://leetcode.com/problems/construct-binary-tree-from-inorder-and-postorder-traversal/description/) |
| Sorted Array to BST | [LeetCode](https://leetcode.com/problems/convert-sorted-array-to-binary-search-tree/description/) |

## Graphs

| Problem | Link |
|---|---|
| Construct Adjacency List from Edges + Nodes | [GfG](https://www.geeksforgeeks.org/problems/print-adjacency-list-1587115620/1) |
| Graph DFS | [GfG](https://www.geeksforgeeks.org/problems/depth-first-traversal-for-a-graph/1) |
| Graph BFS | [GfG](https://www.geeksforgeeks.org/problems/bfs-traversal-of-graph/1) |
| Number of Islands | [LeetCode](https://leetcode.com/problems/number-of-islands/description/) |
| Number of Provinces | [LeetCode](https://leetcode.com/problems/number-of-provinces/description/) |
| Rotten Oranges | [LeetCode](https://leetcode.com/problems/rotting-oranges/) |
| Cycle Detection — Undirected Graph | [GfG](https://www.geeksforgeeks.org/problems/detect-cycle-in-an-undirected-graph/1) |
| Cycle Detection — Directed Graph | [GfG](https://www.geeksforgeeks.org/problems/detect-cycle-in-a-directed-graph/1) |
| Topological Sort | [GfG](https://www.geeksforgeeks.org/problems/topological-sort/1) |
| Bipartite Graph / Graph Coloring | [LeetCode](https://leetcode.com/problems/is-graph-bipartite/) |
| Surrounded Regions | [LeetCode](https://leetcode.com/problems/surrounded-regions/) |
| Shortest Path in Non-Weighted Graph | [GfG](https://www.geeksforgeeks.org/problems/shortest-path-in-undirected-graph-having-unit-distance/1) |
| Dijkstra's Algorithm | [GfG](https://www.geeksforgeeks.org/problems/implementing-dijkstra-set-1-adjacency-matrix/1) |
| Network Delay Time | [LeetCode](https://leetcode.com/problems/network-delay-time/) |
| Path With Minimum Effort | [LeetCode](https://leetcode.com/problems/path-with-minimum-effort/) |
| Swim in Rising Water | [LeetCode](https://leetcode.com/problems/swim-in-rising-water/) |
| Bellman-Ford | [GfG](https://www.geeksforgeeks.org/problems/distance-from-the-source-bellman-ford-algorithm/1) |
| Cheapest Flights Within K Stops | [LeetCode](https://leetcode.com/problems/cheapest-flights-within-k-stops/description/) |
| Prim's MST | [GfG](https://www.geeksforgeeks.org/problems/minimum-spanning-tree/1) |
| Word Ladder | [LeetCode](https://leetcode.com/problems/word-ladder/) |

## DP (Dynamic Programming)

| Episode | Problem | Link |
|---|---|---|
| 02 | Fibonacci | [LeetCode](https://leetcode.com/problems/fibonacci-number/description/) |
| 03 | Climbing Stairs | [LeetCode](https://leetcode.com/problems/climbing-stairs/description/) |
| 04 | House Robber | [LeetCode](https://leetcode.com/problems/house-robber/) |
| 05 | 0/1 Knapsack | [GfG](https://www.geeksforgeeks.org/problems/0-1-knapsack-problem0945/1) |
| 06 | Tabulation — Intro | — |
| 07 | 0/1 Knapsack (Tabulation) | [GfG](https://www.geeksforgeeks.org/problems/0-1-knapsack-problem0945/1) |
| 08 | Subset Sum | [GfG](https://www.geeksforgeeks.org/problems/subset-sum-problem-1611555638/1) |

---

*Source: INSTA channel's Daily Pattern Question series.*
