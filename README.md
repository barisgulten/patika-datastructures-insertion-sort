# Project 1

**[22,27,16,2,18,6]** -> Insertion Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.
3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

---
---

1. 

```
1. [22|, 27, 16, 2, 18, 6] - (n)
2. [22, 27|, 16, 2, 18, 6] - (n-1)
3. [16, 22, 27|, 2, 18, 6] - (n-2)
4. [2, 16, 22, 27|, 18, 6] - (n-3)
5. [2, 16, 18, 22, 27|, 6] -  1
6. [2, 6, 16, 18, 22, 27] 
```

---



2. Big O notation.
   n! = (n.(n+1))/2 = O(n^2)

---



3.

Best case : O(n)

Average case : O (n^2)

Worst case : O(n^2)

---



4. If it is in the miidde it considered as Average Case.  0(n^2)

---

# Project 2.

```
[7,3,5,8,2,9,4,15,6]

1. [7|,3,5,8,2,9,4,15,6]
2. [3,7|,5,8,2,9,4,15,6]
3. [3,5,7|,8,2,9,4,15,6]
4. [3,5,7,8|,2,9,4,15,6]
```
