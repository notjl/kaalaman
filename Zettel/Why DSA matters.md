###### Type: #literature
###### Tags: [[Coding]], [[DSA]]
---
# Why DSA matters (09-09-23 17:58)

**Data Structure** is important in aspect of any program. You would need to put thought on what *"container"* to use for your data. **Arrays** is a common *container* in which people use to store data, as well as **Sets**. There are difference between the two, and that is **Sets** only allow unique data, meaning duplicates are disposed. Why does the type of container matters? Because when we look at the *Searching*, *Insertion*, *Deletion*, and *Reading* of a container, it is important to see the benefits of each container. For example, in sets, it is required for us to perform a *Search* first and then *Insert*. Because we have the need to look whether the element we are inserting is in the set. However, in an array, we have no need to search. If we are inserting at the end of the array, we only simply allocate a memory at the end of the array and insert.

**Algorithm** is as important as Data Structure. The algorithm used to search for an element in an array matters. For example, using ![[Linear Search#Ordered Array]] in a Ordered Array, would take **N** amount of time (N being the length of the array). But using a proper algorithm such as ![[Binary Search]] would take **log N** amount of time because no matter how much data input you have, the steps to find the a certain element in an Ordered Array rises marginally. 

As stated in [[What Data Structure and Algorithms truly is]], DS and A is interrelated, meaning the Algorithm used to interact with the Data Structure matters as well. This is evident because applying Binary Search to a Unordered Array would result in the same of time as you would using Linear Search. This is because, there is no benefit in using Binary Search wherein there is no proper midpoint.

---
## References
-  [[📘 A Common-Sense Guide to Data Structures and Algorithms]]