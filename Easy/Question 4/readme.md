You have arranged a local football match where the supporters are either real madrid or fc barcelona fans. Now you want them to sit in a line such that fans of both teams are alternated  as much as possible. Suppose there are x real madrid supporters and y fc barcelona supporters then positions in line are indexed from 1 to x+y. You have arrange the fans in such a way that the number of integers i(1<=i<=x+y) such that positions with indexes i and i + 1 contain children of different teams(position i has a real madrid fan and position i + 1 has a fc barcelona fan or vice versa) must be as large as possible.
 
### Input format
The single line of the input contains two integers x(Number of real marid fans) and y(number of Fc Barcelona Fans) (1 ≤ x, y ≤ 100), separated by a space.
### Output
Print a line of x + y characters. Print on the i-th position of the line character "r", if the i-th position of your arrangement should have a real madrid fan and "f", if it should have a fc barcelona fan.
Of course, the number of characters "r" should equal x and the number of characters "f" should equal y. If there are multiple optimal solutions, print any of them.
## Sample Input 1
```
4 2
```
## Sample Output 1
```
rfrfrr
```
## Sample Input 1
```
3 3
```
## Sample Output 1
```
rfrfrfr
``` 
 
 

