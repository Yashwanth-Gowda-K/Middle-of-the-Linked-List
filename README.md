# Middle-of-the-Linked-List


Problem Statement
Given the head of a singly linked list, return the middle node. If there are two middle nodes (even length), return the second one.

Examples:
Input: [1,2,3,4,5] → Output: 3

Input: [1,2,3,4,5,6] → Output: 4 (second middle node)

Approach 🚀
I used the slow and fast pointer technique (Floyd’s Tortoise and Hare algorithm) for an optimal solution:

Initialize two pointers, slow and fast, at the head.

Traverse the list:

slow moves 1 node per step.

fast moves 2 nodes per step.

When fast reaches the end, slow points to the middle node!

Why It Works:
Efficiency: O(n) time, O(1) space—no extra memory or double traversals.

Handles edge cases: Works for both odd and even-length lists.
