# Sliding Window Maximum

| | |
|---|---|
| **LeetCode** | [239. Sliding Window Maximum](https://leetcode.com/problems/sliding-window-maximum/) |
| **Difficulty** | Hard |
| **Primary pattern** | Monotonic Deque |

## Problem brief

For every window of width `k` moving from left to right, report the maximum value currently inside the window.

## Example

`nums = [1,3,-1,-3,5,3,6,7]`, `k = 3` → `[3,3,5,5,6,7]`

## Constraints

`1 <= k <= len(nums) <= 10^5`; values fit within signed 32-bit integers.

## Python signature

```python
`class Solution: def maxSlidingWindow(self, nums: list[int], k: int) -> list[int]:`
```

> Read the [official problem statement](https://leetcode.com/problems/sliding-window-maximum/) for the authoritative wording, complete examples, and judge details.

