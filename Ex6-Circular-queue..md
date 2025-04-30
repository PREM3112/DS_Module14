# Ex6 Dequeue Elements from Circular Queue
## DATE: 25/04/2025
## AIM:
To write a C program to delete three elements from the filled circular queue.

## Algorithm
1.Start
2.Define a queue with a fixed size SIZE and initialize front and rear pointers.<br/>
3.Define the deQueue() function to remove and return an element from the front of the queue.<br/>
4.Check if the queue is empty using isEmpty(); if empty, print an error message.<br/>
5.If the queue has one element, reset both front and rear to -1.<br/>
6.If the queue has more than one element, update front to the next index using modulo operation ((front + 1) % SIZE).<br/>
7.Return the removed element from the front of the queue.<br/>
8.End<br/>

## Program:
```
/*
Program to delete three elements from the filled circular queue
Developed by: PREM R
RegisterNumber: 212223240124 
*/

/*#include<stdio.h>
#define SIZE 5 int items[SIZE];
int front =-1, rear =-1;
*/
int deQueue()
{
int element; element=items[front]; if(isEmpty())
{
printf("Queue is Empty!!");
}
else
{
if(front==rear)
{
front=-1; rear=-1;
}
 
else
{
front=(front+1)%SIZE;
}
}
return element;
}

```
## Output:
![image](https://github.com/user-attachments/assets/b9538d69-d8b1-4d9a-8a9f-b4b5ff25542f)



## Result:
Thus, the C program to delete three elements from the filled circular queue is implemented successfully.
