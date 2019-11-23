# DFS-4

## Problem1: Coin distribution(https://leetcode.com/problems/distribute-coins-in-binary-tree/)

Given a binary tree with N nodes, and there are N coins total.

In one move, we may choose two adjacent nodes and move one coin from one node to another.  (The move may be from parent to child, or from child to parent.)

Return the number of moves required to make every node have exactly one coin.

Example 1:

Input: [3,0,0]

Output: 2

Explanation: From the root of the tree, we move one coin to its left child, and one coin to its right child.

Example 2:

Input: [0,3,0]

Output: 3

Explanation: From the left child of the root, we move two coins to the root [taking two moves].  Then, we move one coin from the root of the tree to the right child.

Example 3:

Input: [1,0,2]

Output: 2

Example 4:

Input: [1,0,0,null,3]

Output: 4

## Problem 2: Weight sum of a nested List (https://leetcode.com/problems/nested-list-weight-sum/)

Provided a nested list of integers, return the sum of all integers in the list weighted by their depth.

Each element is either an integer, or a list -- whose elements may also be integers or other lists.

Example 1:

Input: [[1,1],2,[1,1]]

Output: 10

Explanation: Four 1's at depth 2, one 2 at depth 1.

Example 2:

Input: [1,[4,[6]]]

Output: 27

Explanation: One 1 at depth 1, one 4 at depth 2, and one 6 at depth 3; 1 + 4*2 + 6*3 = 27
