Aryan Brought n toys from the market and placed them in a single line on a table. Each toy is numbered from 1 to n such that all the numbers are distinct. While Aryan was  busy his friend Akhil removed some toys from the row. Now Aryan wants to put them back on. 
Aryan defines complexity of a garland to be the number of pairs of adjacent toys with numbers with different parity (remainder of the division by 2). For example, the complexity of 1 4 2 3 5 is 2 and the complexity of 1 3 5 7 6 4 2 is 1.
No one likes complexity, so Aryan wants to minimize the number of such pairs. Find the way to put all toys back in the row , such that the complexity is as small as possible.

### Input
The first line contains a single integer n (1≤n≤100) — the number of toys in the row.

The second line contains n integers p1, p2, …, pn (0≤pi≤n) — the number on the i-th toy, or 0 if it was removed.

### Output
Output a single number — the minimum complexity of the row.

### Sample Input 1
```
5
0 5 0 2 3
```

### Sample Output 1
```
2
```



