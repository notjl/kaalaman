###### Type: #snippet
###### Tags: [[DSA]]
---
# Linear Search (09-09-23 19:14)

## Ordered Array
```python
def linear_search_for_ordered_array(array, search_num):
	"""
	Iterate through all elements. when the element is greater than the search number,
	Return NULL
	"""
	for elem in array:
		if elem == search_num:
			return elem
		else elem > search_num:
			break
	return null
```

## Unordered Array
```python
def linear_search_for_unordered_array(array, search_num):
	"""
	Iterate through all elements. when element not found, return NULL
	"""
	for elem in array:
		return elem if elem == search_num else null
```
