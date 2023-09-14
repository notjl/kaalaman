###### Type: #literature
###### Tags: [[Coding]], [[DSA]]
---
# Big O is not absolute (12-09-23 17:53)

We have studied that [[Big O helps with speeding up code]] but that doesn't mean that this is an absolute rule. Not unless we compare two algorithms with the same apparent Big O category. We can take ![[Bubble Sort#Bubble Sort (11-09-23 21 42)]] which as we know, is a $O(n^2)$ algorithm because it has to *"inflate"* the largest element so it goes to the top (in this case to the left).

There's also  ![[Selection Sort#Selection Sort (12-09-23 17 45)]] which in this case halves the amount of steps taken unlike [[Bubble Sort]] because instead of swapping every comparison, we may do one or none at all. So, it should be $O(n^2 / 2)$, right?

Well, in the case of the notation, we ignore constants. Because no matter how much constant steps an algorithm take, the notation only cares about the size of the data which is the $n$ of the notation. That would mean [[Selection Sort]] is a $O(n^2)$ algorithm.

That doesn't mean we should ignore [[Selection Sort]]'s speed either. Big O helps us understand the *worst-case* efficiency of an algorithm but that doesn't mean we should deprave ourselves of understanding the deeper machination of an algorithm. In a scenario where you are to choose between two algorithms with the same *time complexity*, you would still choose the faster algorithm. How would you go about doing that?

You have to pull apart both algorithms and learn why one is gonna be better than the other. 

---
## References
- [[📘 A Common-Sense Guide to Data Structures and Algorithms]]