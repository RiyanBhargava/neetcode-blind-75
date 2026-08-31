# Reshape the Matrix

| | |
|---|---|
| **LeetCode** | [566. Reshape the Matrix](https://leetcode.com/problems/reshape-the-matrix/) |
| **Difficulty** | Easy |
| **Primary pattern** | Matrix / Index Mapping |

## Problem brief

Rearrange a matrix into `r` rows and `c` columns while preserving row-major order. If the requested dimensions are incompatible, return the original matrix.

## Example

`[[1,2],[3,4]]`, `r = 1`, `c = 4` → `[[1,2,3,4]]`

## Constraints

The input matrix is non-empty; dimensions and values are small integers.

## Python signature

```python
`class Solution: def matrixReshape(self, mat: list[list[int]], r: int, c: int) -> list[list[int]]:`
```

> Read the [official problem statement](https://leetcode.com/problems/reshape-the-matrix/) for the authoritative wording, complete examples, and judge details.

