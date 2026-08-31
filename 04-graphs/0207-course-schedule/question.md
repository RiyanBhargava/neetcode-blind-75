# Course Schedule

| | |
|---|---|
| **LeetCode** | [207. Course Schedule](https://leetcode.com/problems/course-schedule/) |
| **Difficulty** | Medium |
| **Primary pattern** | Topological Sort / Cycle Detection |

## Problem brief

Given course prerequisite pairs, determine whether every course can be completed. Completion is impossible when the dependency graph contains a cycle.

## Example

`numCourses = 2`, `prerequisites = [[1,0]]` → `True`

## Constraints

`1 <= numCourses <= 2000`; prerequisite pairs are unique.

## Python signature

```python
`class Solution: def canFinish(self, numCourses: int, prerequisites: list[list[int]]) -> bool:`
```

> Read the [official problem statement](https://leetcode.com/problems/course-schedule/) for the authoritative wording, complete examples, and judge details.

