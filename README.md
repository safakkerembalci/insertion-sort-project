# **insertion sort project**

## **Proje 1**

[22,27,16,2,18,6] -> Insertion Sort

---

1-Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

**Cevap:**

***Insertion Sort için;***                   

[22,27,16,2,18,6]

[16,22,27,2,18,6]

[2,16,22,27,18,6]

[2,16,18,22,27,6]

[2,6,16,18,22,27]

***Selection Sort için;***

[2,27,16,22,18,6]

[2,6,16,22,18,27]

[2,6,16,22,18,27]

[2,6,16,18,22,27]

[2,6,16,18,22,27]

---

2-Big-O gösterimini yazınız.

**Cevap:**

n!= n*(n-1)/2 = (n^2*n)/2 bu formülden Big-O gösterimi O(n^2) şeklinde olacaktır.

---

Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

---

3-Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

**Cevap:**

Dizi sıralandıktan sonra 18 sayısı ortada olduğu için **AVERAGE CASE** kapsamına girmektedir.

## **Proje 2**

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

**Cevap:**

***Insertion Sort için;***

[3,7,5,8,2,9,4,15,6]

[3,5,7,8,2,9,4,15,6]

[3,5,7,8,2,9,4,15,6]

[2,3,5,7,8,9,4,15,6]

[2,3,5,7,8,9,4,15,6]

[2,3,4,5,7,8,9,15,6]

[2,3,4,5,7,8,9,15,6]

[2,3,4,5,7,8,9,6,15]

***Selection Sort için;***

[2,3,5,8,7,9,4,15,6]

[2,3,5,8,7,9,4,15,6]

[2,3,4,8,7,9,5,15,6]

[2,3,4,5,7,9,8,15,6]

[2,3,4,5,6,9,8,15,7]

[2,3,4,5,6,7,8,15,9]

[2,3,4,5,6,7,8,15,9]

[2,3,4,5,6,7,8,9,15]
