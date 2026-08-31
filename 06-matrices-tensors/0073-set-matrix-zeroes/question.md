# Set Matrix Zeroes

| | |
|---|---|
| **LeetCode** | [73. Set Matrix Zeroes](https://leetcode.com/problems/set-matrix-zeroes/) |
| **Difficulty** | Medium |
| **Primary pattern** | In-place Matrix Marking |

## Problem brief

If any matrix cell is zero, set its entire row and column to zero. Modify the matrix in place, ideally with constant extra space.

## Example

`[[1,1,1],[1,0,1],[1,1,1]]` → `[[1,0,1],[0,0,0],[1,0,1]]`

## Constraints

`1 <= rows, columns <= 200`; values fit within signed 32-bit integers.

## Python signature

```python
`class Solution: def setZeroes(self, matrix: list[list[int]]) -> None:`
```

> Read the [official problem statement](https://leetcode.com/problems/set-matrix-zeroes/) for the authoritative wording, complete examples, and judge details.

