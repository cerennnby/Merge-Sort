# Merge-Sort
Patika.dev / Merge Sort 

[16,21,11,8,12,22] -> Merge Sort
Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

       [16,21,11,8,12,22]

       'Separated to two parts at every step:

       [16,21,11]         [8,12,22]

       [16,21] [11]       [8,12] [22]

       [16] [21] [11]     [8] [12] [22]

       'Then sorted and combined:

       [16,21] [11]       [8,12] [22]

       [11,16,21]         [8,12,22] 

       [8,11,12,16,21,22]
       
       Big-O ; 2^x=n  logn = x  so the O notation is, O(nlogn)
