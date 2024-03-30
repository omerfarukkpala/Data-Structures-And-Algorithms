## Data Structures And Algorithms    
# Merge-Sort-Project  
# Binary-Search-Tree-Project    
# Insertion-Sort-Project
Given array: [16,21,11,8,12,22] -> Merge Sort
# 1- Write down the steps of the given array according to the sorting type.

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
 
 # 2- Write the Big-O notation.
 
 O(nlogn)
# PatikaDev Data Structures and Algorithms Binary Search Tree
## Write the Binary Search Tree steps for the array [7, 5, 1, 8, 3, 6, 0, 9, 4, 2].
### Example: root is x. To the right of root, find y. To the left of y, find z, and so on.
Root:7

                          7
                         / \
                        5   8
                       / \   \
                      1   6   9
                     / \
                    0   3
                       / \
                      2   4

## Data Structures and Algorithms Start
Patika.Dev DataStructures-Algorithms 
#### Kodluyoruz Insertion Sort Project
## Example 1
[22,27,16,2,18,6] -> Insertion Sort
Write down the steps of the given array according to the sorting type.

1- [22,27|16,2,18,6]  
2- [16,22,27|2,18,6]  
3- [2,16,22,27|18,6]  
4- [2,16,18,22,27|6]  
5- [2,6,16,18,22,27]

### 2.Write the Big-O notation.

O(n^2)

#### 3.Time Complexity: Average case: The number we are looking for is in the middle, Worst case: The number we are looking for is at the end, Best case: The number we are looking for is at the beginning.

Average case: O(n^2)  
Worst case: O(n^2)  
Best case: O(n)

#### 4.After sorting the array, in which case does the number 18 fall into? Write down.

It falls into the Average case because it is in step 4.

##### Example 2
Write the first 4 steps of the [7,3,5,8,2,9,4,15,6] array according to Insertion Sort.
```
1- [3,7|5,8,2,9,4,15,6]  
2- [3,5,7|8,2,9,4,15,6]  
3- [3,5,7,8|2,9,4,15,6]  
4- [2,3,5,7,8|9,4,15,6]
```
Content
