In a class of n students, there are 5 subjects in total(Maths, Physics, Chemistry, Computer Science, English) and each subject is marked out of 100. Each student has a name and a unique admission number. Your teacher has assigned you with a task in which you have to sort the names of students in the following priority order:
Students with the highest total marks in all 5 subjects are ranked first
If some students have equal total marks, then sort them according to the total marks obtained in physics, chemistry and maths.
If some students have the same total marks in physics, chemistry and maths then sort according to their name.
If few students have the same name also, then sort them according to their admission numbers.
### Input format
First line contains an integer n(1<n<20), representing the number of students.
The next n line contains student details with each line containing details of students as:
Name AdmissionNumber Physics Chemistry Maths English Computer Science

### Output format
Output only the name and admission order of students after sorting them.

## Sample Test Case 1:
```
4
Danish 132 76 66 95 40 77
Lakshya 133 55 44 97 94 99
Shreyansh 144 89 98 99 99 100
Ayush 145 90 90 90 30 54
```

## Sample Output 1:
```
Shreyansh 144
Lakshya 133
Ayush 145
Danish 132
```
