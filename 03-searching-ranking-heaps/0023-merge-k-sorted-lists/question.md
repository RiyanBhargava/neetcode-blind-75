# Merge k Sorted Lists

| | |
|---|---|
| **LeetCode** | [23. Merge k Sorted Lists](https://leetcode.com/problems/merge-k-sorted-lists/) |
| **Difficulty** | Hard |
| **Primary pattern** | Heap / Multiway Merge |

## Problem brief

Merge several individually sorted linked lists into one sorted linked list.

## Example

`[[1,4,5],[1,3,4],[2,6]]` → `[1,1,2,3,4,4,5,6]`

## Constraints

Up to `10^4` lists and `10^4` nodes overall; each input list is sorted ascending.

## Python signature

```python
`class Solution: def mergeKLists(self, lists: list[Optional[ListNode]]) -> Optional[ListNode]:`
```

> Read the [official problem statement](https://leetcode.com/problems/merge-k-sorted-lists/) for the authoritative wording, complete examples, and judge details.

