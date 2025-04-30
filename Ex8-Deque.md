# Ex8 Deque
## DATE: 25/04/2025
## AIM:
To write a C function to count the number of elements present in the deque.

## Algorithm
1.Start<br/>
2.Define a function count() that takes an array arr as input.<br/>
3.Initialize a counter c to track the number of non-zero elements.<br/>
4.Loop through the array from index 0 to MAX-1.<br/>
5.For each element, check if it's non-zero.<br/>
6.If the element is non-zero, increment the counter c<br/>.
7.Return the final count of non-zero elements in the array.<br/>
8.End<br/>


## Program:
```
/*
Program to count the number of elements present in the deque
Developed by: PREM R
RegisterNumber: 212223240124
*/

/*#include <stdio.h> #define MAX 10
void addFront(int *, int, int *, int *); void addRear(int *, int, int *, int *); int delFront(int *, int *, int *); intdelRear(int *, int *, int*);
void display(int *); int count(int *);
*/
int count(int *arr) { int c = 0, i; for(i=0;i<MAX;i++)
{
if(arr[i]!=0)
{
c=c+1;
}
}
return c;
}

```
## Output:

![image](https://github.com/user-attachments/assets/f72ad690-beb7-4a24-ae46-35aa9f5df7c7)


## Result:
Thus, the C code to count the number of elements present in the deque is implemented successfully.
