# Ex10 Applications of Queue – FCFS
## DATE: 25/04/2025
## AIM:
To write a C function to calculate the turnaround time of each process given their burst time and waiting time in First Come first Serve scheduling algorithm.
## Algorithm

1.Start with process, burst time, and waiting time arrays.<br/>
2.Loopthrough each process from i= 0 to n-1.<br/>
3.Compute tat[i] = burst_time[i] + wait_time[i].<br/>
4.End the algorithm.<br/>


## Program:
```
/*
Program to find and display the priority of the operator in the given Postfix expression
Developed by: PREM R
RegisterNumber:  212223240124
*/

int turnaroundtime( int proc[], int n,int burst_time[], int wait_time[], int tat[])
 {
// calculating turnaround time byadding
// burst_time[i] + wait_time[i] int i;
for ( i = 0; i < n ; i++)
tat[i] = burst_time[i] + wait_time[i]; return 0;
}
```

## Output:

![image](https://github.com/user-attachments/assets/eca04d1e-476d-4d1e-91d6-d3cc1adfb070)


## Result:
Thus, the C function to calculate the turnaround time of each process given their burst time and waiting time in First Come first Serve scheduling algorithm is implemented successfully.
