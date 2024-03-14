# Data Structures and Algorithms Projects

## HW1

### Insertion Sort

```
[22,27,16,2,18,6]
[22,27,16,2,18,6] => step 1
[22,16,27,2,18,6] => step 2
[16,22,27,2,18,6] => step 3
[16,22,2,27,18,6] => step 4
[16,2,22,27,18,6] => step 5
[2,16,22,27,18,6] => step 6
[2,16,22,18,27,6] => step 7
[2,16,18,22,27,6] => step 8
[2,16,18,22,6,27] => step 9
[2,16,18,6,22,27] => step 10
[2,16,6,18,22,27] => step 11
[2,6,16,18,22,27] => step 12

```

### Big-O Notation

```
step 1 => n
step 2 => n-1
step 3 => n-2
.
.
.
step 12 => 1
n+(n-1)+(n-2)+...+1 = (n^2+n)/2 => O(n^2)
```

### Time Complexity

```
1. Average Case
```

### Selection Sort

```
[7,3,5,8,2,9,4,15,6]
[2,3,5,8,7,9,4,15,6] => step 1
[2,3,5,8,7,9,4,15,6] => step 2
[2,3,4,8,7,9,5,15,6] => step 3
[2,3,4,5,7,9,8,15,6] => step 4
```

## HW2

### Merge Sort

```
                                    [16,21,11,8,12,22]
step 1 =>		     [16,21,11]                [8,12,22]
step 2 =>		  [16,21]  [11]              [8,12]  [22]
step 3 =>	        [16]  [21]  [11]           [8]  [12]  [22]
step 4 =>	         [16,21]   [11]             [8,12]   [22]
step 5 =>		    [11,16,21]                [8,12,22]
step 6 =>			     [8,11,12,16,21,22]
```

### Big-O Notation

```
O(nlogn)
```

## HW3

### Binary Search Tree

```
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]
            7
           / \
          5   8
         / \   \
        1   6   9
       / \     /
      0   3   9
         / \
        2   4
```
