Given a two-dimensional array or matrix of size n*m, Write an algorithm to print the given matrix in a zigzag manner or in other words print all the diagonals from bottom to up in  the matrix starting from the position p as stated below:
For p=1, Start from 0,0 position
For p=2, Start from 0,m-1 position
For p=3, Start from n-1,m-1 position
For p=4, Start from n-1,0 position
### Input Format
First line contains 3 integers n, m and p separated by  spaces.
Next n line contains m integers.

### Output format
Print diagonal traversal of  n*m integers starting from specified positions. Print each diagonal on a separate line. (See the sample test cases for clear understanding of the question).


### Sample Test case 1
```
3 3 1
1 2 3
4 5 6
7 8 9
```
### Sample Test Case output 1
```
1
4 2
7 5 3
8 6
9
```

### Sample Test case 2
```
3 3 2
1 2 3
4 5 6
7 8 9
```
### Sample Test Case output 2
```
3
6 2
9 5 1
8 4
7
```

### Sample Test case 3
```
3 3 3
1 2 3
4 5 6
7 8 9
```
### Sample Test Case output 3
```
9
8 6
7 5 3
4 2
1
```

### Sample Test case 4
```
3 3 4
1 2 3
4 5 6
7 8 9
```
### Sample Test Case output 4
```
7
8 4
9 5 1
6 2
3
```





