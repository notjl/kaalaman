###### Type: #snippet
###### Tags: [[LeetCode]]
---
# Two Sums (11-09-23 21:10)

## $O(n^2)$
```python
def two_sum(nums):
    for i in range(len(nums)):
        for j in range(i+1, len(nums)):
            if nums[i] + nums[j] == target:
                return [i, j]
```

