# Evaluate Division

| | |
|---|---|
| **LeetCode** | [399. Evaluate Division](https://leetcode.com/problems/evaluate-division/) |
| **Difficulty** | Medium |
| **Primary pattern** | Weighted Graph |

## Problem brief

Use known ratios between variables to evaluate requested ratios. Return `-1.0` when a relationship cannot be derived.

## Example

Equations `a/b=2`, `b/c=3`; query `a/c` → `6.0`

## Constraints

Inputs are valid, denominators are non-zero, and known equations do not contradict one another.

## Python signature

```python
`class Solution: def calcEquation(self, equations, values, queries) -> list[float]:`
```

> Read the [official problem statement](https://leetcode.com/problems/evaluate-division/) for the authoritative wording, complete examples, and judge details.

