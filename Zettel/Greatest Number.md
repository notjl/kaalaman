###### Type: #snippet
###### Tags: [[DSA]]
---
# Greatest Number (11-09-23 22:44)

## Exercise
```python
def greatest_number(array):
	for i in array:
		is_i_val_the_greatest = True
		for j in array:
			if j > i:
				is_i_val_the_greatest = False
		if is_i_val_the_greatest:
			return i
```

## Solution
```python
def greatest_number(array);
	greatest_number = array[0]
	for i in array:
		if i > greatest_number:
			greatest_number = i
	return greatest_number
```