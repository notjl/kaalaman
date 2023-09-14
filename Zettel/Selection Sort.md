###### Type: #snippet
###### Tags: [[DSA]]
---
# Selection Sort (12-09-23 17:45)

```python
def selection_sort(array):
	for i in range(len(array)):
		lowest_index = i
		for j in range(len(array) + 1)
			if array[j] < array[lowest_index]:
				lowest_index = j

		array[i], array[lowest_index] = array[lowest_index], array[i]
	
	return array
```
