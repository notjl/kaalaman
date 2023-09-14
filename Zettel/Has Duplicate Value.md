###### Type: #snippet
###### Tags: [[DSA]]
---
# Has Duplicate Value (11-09-23 21:53)

## $O(n^2)$
```python
def has_duplicate_array_n2(array):
	for i in range(len(array)):
		for j in range(len(array)):
			if i != j and array[i] == array[j]:
					return true
	return false
```

## $O(n)$
```python
def has_duplicate_array(array):
	existing_numbers = []
	for elem in array:
		if elem in existing_numbers:
			return true
		else
			existing_numbers.append(elem)
	return false
```