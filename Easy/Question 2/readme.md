You are given an array consisting of N integers. In every operation you perform, you are allowed to choose any 2 elements from the array and replace both of them with a new number in the array which is equal to the sum of both numbers . The position where you insert this new element does not matter . For example, from the array [5,2,1] you can have the following arrays in possibility: [5,3], [7,1] and [2,6].

Your task is to find the maximum possible number of elements divisible by 4 that are in the array after performing the above operation any(possibly, zero) number of times.	
### Input Format
First line contains the number of test cases t(1<t<10). The first line of each text case contains the size N(1<N<100) of the array. The second line of each array contains the N array elements(1<= Ni<=10000).
### Output Format
For every test Case print one Number, that is the maximum possible number of elements divisible by 4 .
## Sample Input 1
```
3
5
4 2 1 3 2
5
4 4 4 4 4
6
1 1 1 1 2 2
```
## Sample Output 1
```
3
5
2
```

