Till now, we were scheduling the processes according to their arrival time (in FCFS scheduling). However, SJF scheduling algorithm, schedules the processes according to their burst time.

In SJF scheduling, the process with the lowest burst time, among the list of available processes in the ready queue, is going to be scheduled next.

However, it is very difficult to predict the burst time needed for a process hence this algorithm is very difficult to implement in the system.

### Advantages of SJF
1.) Maximum throughput

2.) Minimum average waiting and turnaround time

### Disadvantages of SJF

1.) May suffer with the problem of starvation

2.) It is not implementable because the exact Burst time for a process can't be known in advance.

There are different techniques available by which, the CPU burst time of the process can be determined. We will discuss them later in detail.

Example
In the following example, there are five jobs named as P1, P2, P3, P4 and P5. Their arrival time and burst time are given in the table below.

PID	Arrival Time	Burst Time	Completion Time	    Turn Around Time	Waiting Time
1	  1	                7	        8       	            7	            0
2	  3	                3	        13	                    10	            7
3	  6	                2	        10	                    4	            2
4	  7	                10	        31	                    24	            14
5	  9	                8	        21	                    12             	4
Since, No Process arrives at time 0 hence; there will be an empty slot in the Gantt chart from time 0 to 1 (the time at which the first process arrives).

According to the algorithm, the OS schedules the process which is having the lowest burst time among the available processes in the ready queue.

Till now, we have only one process in the ready queue hence the scheduler will schedule this to the processor no matter what is its burst time.

This will be executed till 8 units of time. Till then we have three more processes arrived in the ready queue hence the scheduler will choose the process with the lowest burst time.

Among the processes given in the table, P3 will be executed next since it is having the lowest burst time among all the available processes.

So that's how the procedure will go on in shortest job first (SJF) scheduling algorithm.

os SJF scheduling algorithm
         Avg Waiting Time = 27/5

