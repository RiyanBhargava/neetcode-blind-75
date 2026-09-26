# LRU Cache

| | |
|---|---|
| **LeetCode** | [146. LRU Cache](https://leetcode.com/problems/lru-cache/) |
| **Difficulty** | Medium |
| **Primary pattern** | Hash Map / Doubly Linked List |

## Problem brief

Implement a fixed-capacity cache. Reading or updating a key makes it most recently used; insertion beyond capacity evicts the least recently used key. Both operations must be average `O(1)`.

## Example

Capacity `2`; put `(1,1)`, put `(2,2)`, get `1`, put `(3,3)` → key `2` is evicted

## Constraints

`1 <= capacity <= 3000`; up to `2 * 10^5` calls are made.

## Python signature

```python
`class LRUCache:`
```

> Read the [official problem statement](https://leetcode.com/problems/lru-cache/) for the authoritative wording, complete examples, and judge details.

