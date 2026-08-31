# K Closest Points to Origin

| | |
|---|---|
| **LeetCode** | [973. K Closest Points to Origin](https://leetcode.com/problems/k-closest-points-to-origin/) |
| **Difficulty** | Medium |
| **Primary pattern** | Heap / Distance |

## Problem brief

Given points on a 2D plane, return the `k` points with the smallest Euclidean distance from the origin. Any valid order is accepted.

## Example

`points = [[1,3],[-2,2]]`, `k = 1` → `[[-2,2]]`

## Constraints

`1 <= k <= len(points) <= 10^4`; point coordinates are integers.

## Python signature

```python
`class Solution: def kClosest(self, points: list[list[int]], k: int) -> list[list[int]]:`
```

> Read the [official problem statement](https://leetcode.com/problems/k-closest-points-to-origin/) for the authoritative wording, complete examples, and judge details.

