# Time Based Key-Value Store

| | |
|---|---|
| **LeetCode** | [981. Time Based Key-Value Store](https://leetcode.com/problems/time-based-key-value-store/) |
| **Difficulty** | Medium |
| **Primary pattern** | Hash Map / Binary Search |

## Problem brief

Store multiple timestamped values for a key. A lookup returns the value with the greatest timestamp not exceeding the requested time, or an empty string when none exists.

## Example

Set `foo=bar` at time `1`; get `foo` at time `3` → `bar`

## Constraints

Timestamps supplied to `set` are strictly increasing; up to `2 * 10^5` calls are made.

## Python signature

```python
`class TimeMap:`
```

> Read the [official problem statement](https://leetcode.com/problems/time-based-key-value-store/) for the authoritative wording, complete examples, and judge details.

