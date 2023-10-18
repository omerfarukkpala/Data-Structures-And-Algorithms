# Data Structures And Algorithms
PatikaDev Data Structures and Algorithms

# Kodluyoruz-Merge-Sort-Project

Given array: [16,21,11,8,12,22] -> Merge Sort



1- Write down the steps of the given array according to the sorting type.

```
                [16,21,11,8,12,22]
               /                 \
     [16,21,11]                  [8,12,22]
       /     \                     /     \
  [16,21]   [11]               [8,12]   [22]
   /  \       |                 /  \      |
[16] [21]   [11]              [8] [12]  [22]
 \    /       |                \   /      |
[16,21]     [11]               [8,12]   [22]
     \      /                     \      /
    [11,16,21]                  [8,12,22]
            \                    /
               [8,11,12,16,21,22]
 ```

 2- Write the Big-O notation.

 ```
 O(nlogn)
