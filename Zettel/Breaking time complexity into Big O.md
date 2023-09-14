###### Type: #literature
###### Tags: [[Coding]], [[DSA]]
---
# Breaking time complexity into Big O (09-09-23 20:52)

Time complexity is basically the speed of the algorithm without regards to the hardware. It is rather the amount of steps of which the code takes in order to get the result.

With the use of the **Big O Notation**, we can have consistent expression of the algorithms *speed* which we can compare to each other and see what is the better algorithm to use. As shown in [[Why DSA matters]], we have shown **N** as a variable to determine the complexity or steps taken by algorithm

Big O notation just uses **O(-)** and then the corresponding complexity of the algorithm  

Linear Search for Ordered Array has an **O(N)** time complexity because we simply iterate through an array and see whether it is the desired element. This is despite the conditional in which we stop the iteration when we reach a greater number than the query. It is disregarded since if the input is larger than the second last element, it would still iterate through it all.

Whilst Binary Search for Ordered Array has an **O(log N)** because no matter the size of an array, it will take less steps to find the desired number since the algorithm slices the array into two and determine whether the query is in the two sliced array. It will keep slicing the arrays into smaller chunks until it finds (or not) the query in the array.

The fastest and best Big O is **O(1)** which means the algorithm is constant. This would mean no matter the size of the input, it would take "one step" to solve. No matter how many steps it is technically in a function, what matters most it doesn't make use of any iteration.

This is a bad simplification, but we can simplify determination of a function's Big O notation by:
- Single and linear iteration means it is *O(N)*
- Halving an iteration means it is *O(log N)*
- No iteration means it is *O(1)*

In essence, Big O helps us determine whether our program is efficient despite the hardware.

---
## References
- [[📘 A Common-Sense Guide to Data Structures and Algorithms]]