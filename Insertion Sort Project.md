Project =>
a) [22,27,16,2,18,6] -> Insertion Sort
  Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
  Big-O gösterimini yazınız.
  Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
  Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

b) [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.


-------------------------------------------
Solution:

a) 
For Insertion Sort:

1- [2,27,16,22,18,6] (22 and 2)

2- [2,6,16,22,18,27] (27 and 6)

3- [2,6,16,22,18,27] (16 and 16)

4- [2,6,16,18,22,27] (18 and 22)


For Big-O => O(n^2)

For case => Avarage Case. Because as you can see 18 is in the middle of the array.



b)
For Insertion Sort:

1- [2,3,5,8,7,9,4,15,6] (2 and 7)

2- [2,3,5,8,7,9,4,15,6] (3 and 3) nothing changed

3- [2,3,4,8,7,9,5,15,6] (4 and 5)

4- [2,3,4,5,7,9,8,15,6] (5 and 8) - this is the first 4 step for Insertion Sort.



