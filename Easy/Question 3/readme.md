You are given an array of n integers. You want to make all the numbers in this array as odd. In one operation you can select two indices i and j (i≠j) and replace ai with (ai+aj).

Find the minimum number of operations needed to make all the numbers odd. If there is no way to do it, then print −1.

### Input Format
The first line contains an integer t (1≤t≤102) — the number of test cases in the input.

Then t test cases follow.

The first line of the test case contains one integer n (1≤n≤2⋅105).

The second line of the test case contains n space-separated integers ai (1≤ai≤106)−ai is the ith number.

It is guaranteed that the sum of n does not exceed 2⋅105(∑n≤2⋅105).

### Output
For each test case, If it is impossible to make all the numbers odd then print −1, otherwise print the minimum number of operation needed to make all the numbers odd.

## Sample Input 1
```
4
4
1 4 3 2
5
1 4 3 2 5
6
1 2 6 5 3 4
3
4 2 6

```

## Sample Output 1
```
2
2
3
-1
```
