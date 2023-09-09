###### Type: #snippet
###### Tags: [[DSA]]
---
# Binary Search (09-09-23 19:24)

```python
def bin_search(array, search_num, lower_bound, upper_bound):
	middle_point = (lower_bound + upper_bound) // 2

	if search_num == array[middle_point]:
		return middle_point
	elif array[middle_point] > search_num:
		return bin_search(array, search_num, lower_bound, middle_point-1)
	elif array[middle_point] < search_num:
		return bin_search(array, search_num, middle_point+1, upper_bound)

	return null
```
