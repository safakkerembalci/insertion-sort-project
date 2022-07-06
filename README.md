# **Insertion Sort Project**

## **Project 1**

[22,27,16,2,18,6] -> Insertion Sort

---

1-Write the stages of the above sequence according to the sort type.

**Answer:**

***For Insertion Sort;***                   

[22,27,16,2,18,6]

[16,22,27,2,18,6]

[2,16,22,27,18,6]

[2,16,18,22,27,6]

[2,6,16,18,22,27]

***For Selection Sort;***

[2,27,16,22,18,6]

[2,6,16,22,18,27]

[2,6,16,22,18,27]

[2,6,16,18,22,27]

[2,6,16,18,22,27]

---

2-Write Big-O notation.

**Answer:**

n!= n*(n-1)/2 = (n^2*n)/2 from this formula, Big-O representation will be O(n^2).

---

Time Complexity: 
Average case: The number we are looking for is in the middle,
Worst case: The number we are looking for is at the end,
Best case: The number we are looking for is at the beginning of the array.

---

3-What case does the number 18 fall into after the array is sorted? Write.

**Answer:**

Since the number 18 is in the middle after the array is sorted, it falls within the scope of **AVERAGE CASE**.

## **Project 2**

[7,3,5,8,2,9,4,15,6] Write the first 4 steps of the array according to the Insertion Sort.

**Answer:**

***For Insertion Sort;***

[3,7,5,8,2,9,4,15,6]

[3,5,7,8,2,9,4,15,6]

[3,5,7,8,2,9,4,15,6]

[2,3,5,7,8,9,4,15,6]

[2,3,5,7,8,9,4,15,6]

[2,3,4,5,7,8,9,15,6]

[2,3,4,5,7,8,9,15,6]

[2,3,4,5,7,8,9,6,15]

***For Selection Sort;***

[2,3,5,8,7,9,4,15,6]

[2,3,5,8,7,9,4,15,6]

[2,3,4,8,7,9,5,15,6]

[2,3,4,5,7,9,8,15,6]

[2,3,4,5,6,9,8,15,7]

[2,3,4,5,6,7,8,15,9]

[2,3,4,5,6,7,8,15,9]

[2,3,4,5,6,7,8,9,15]
