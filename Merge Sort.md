# Project 2


[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.



# Solution:

For Merge Sort:

1- [16,21,11] and [8,12,22] Sliced in the middle.

2- [16,21] & [11] & [8,12] & [22]

3- [16] & [21] & [11] & [8] & [12] & [22] All indexs are one element int this moment.

4- [16,21] & [8,11] & [12,22] merging with less in the left style.

5- [8,11,16,21] & [12,22] "

6- [8,11,12,16,21,22] -result.

For Big-O => O(nlogn)
