# Patika-Merge-Sort-Odevi
1) [16,21,11,8,12,22] 
Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

- [16, 21, 11] - [8, 12, 22]
- [16, 21]  [11] - [8, 12] [22]
- [16] [21] [11] - [8] [12] [22]
- [16, 21]  [11] - [8, 12] [22]
- [11, 16, 21] - [8, 12, 22]
- [8, 11,12, 16, 21, 22]

2) Big-O gösterimini yazınız.
Step 1 -> n
Step 2 -> n/2
Step 3 -> n/4
....
Step (n-1) -> (n-1)/2^(n-2)

sum = n + n/2 + ... = n(1 + 1/2 + ...) = nlogn
O(nlogn)
