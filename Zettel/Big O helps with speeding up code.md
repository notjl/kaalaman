###### Type: #literature
###### Tags: [[Coding]], [[DSA]]
---
# Big O helps with speeding up code (11-09-23 21:28)

Since **Big O** helps with us identifying our codes worse-case steps it'll take. With that information, we can refactor to better the speeds of our program. For example, we have ![[Bubble Sort]]
This is an example of $O(n^2)$ , here's an example as well: ![[Has Duplicate Value#$O(n 2)$]]
We can see here that we are using a nested for-loop to check whether an element is the same with the other elements in the array. We can simplify by simply doing this: ![[Has Duplicate Value#$O(n)$]]
Here we can see that instead of having a nested iteration, using a single for-loop and checking whether the element we iterated is inside a temporary container exists. If it does not, then we will append it to the temporary container. This goes on and on for the entirety of the array, if it does match a number, it will return true, but if it doesn't, then it will return false.

With this example, we can work on this exercise: ![[Greatest Number#Exercise]]
And the solution is: ![[Greatest Number#Solution]]
We simply store the first element as the *"greatest number"*, then iterate through the array and check whether the element is greater than the *greatest_number* if it, replace the value of the *greatest_number*. 

---
## References
-  [[📘 A Common-Sense Guide to Data Structures and Algorithms]]