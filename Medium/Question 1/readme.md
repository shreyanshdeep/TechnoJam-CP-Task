You are given a 2-d matrix of size n*m, an integer d which represents the direction of traversal(clockwise or anticlockwise ) and p which represents the starting index.  
You are required to print the given array in spiral  form.For example  the spiral from of the following array starting from position 0,0 in clockwise manner will be :
### Matrix : 
```
1 2 3
4 5 6
7 8 9
```
### Spiral Form: 
```
1 2 3 6 9 8 7 4 5
```
 The direction and starting position will be set according to the following instructions:
* If d=1, you are required to print the array in clockwise form.
* If d=2, you are required to print the array in anti-clockwise form.
* If p=1, you will start from index 0,0
* If p=2, you will start from index 0,m-1
* If p=3, you will start from index n-1,m-1
* If p=3, you will start from index n-1,0
### Input Format
First line contains integers n(1<=n<=10),m(1<=m<=10),d,p separated by spaces.
Next n line contains m elements of each row.

### Output Format
Print n*m elements in one line separated by spaces.

### Sample Input 1
```
3 3 2 1
1 2 3
4 5 6
7 8 9
```

### Sample Output 1
```
1 4 7 8 9 6 3 2 5
```

### Sample Input 2
```
3 3 1 3
1 2 3
4 5 6
7 8 9
```

### Sample Output 2
```
9 8 7 4 1 2 3 6 5
```




