# Merge Intervals

| | |
|---|---|
| **LeetCode** | [56. Merge Intervals](https://leetcode.com/problems/merge-intervals/) |
| **Difficulty** | Medium |
| **Primary pattern** | Sorting / Intervals |

## Problem brief

Merge every pair of overlapping closed intervals and return the resulting non-overlapping intervals.

## Example

`[[1,3],[2,6],[8,10],[15,18]]` → `[[1,6],[8,10],[15,18]]`

## Constraints

`1 <= len(intervals) <= 10^4`; each interval has `start <= end`.

## Python signature

```python
`class Solution: def merge(self, intervals: list[list[int]]) -> list[list[int]]:`
```

> Read the [official problem statement](https://leetcode.com/problems/merge-intervals/) for the authoritative wording, complete examples, and judge details.

