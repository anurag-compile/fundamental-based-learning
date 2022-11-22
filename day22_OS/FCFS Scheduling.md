# FCFS Scheduling
First come first serve (FCFS) scheduling algorithm simply schedules the jobs according to their arrival time. The job which comes first in the ready queue will get the CPU first. The lesser the arrival time of the job, the sooner will the job get the CPU. FCFS scheduling may cause the problem of starvation if the burst time of the first process is the longest among all the jobs.

### Advantages of FCFS
Simple

Easy

First come, First serv

### Disadvantages of FCFS

The scheduling method is non preemptive, the process will run to the completion.
Due to the non-preemptive nature of the algorithm, the problem of starvation may occur.
Although it is easy to implement, but it is poor in performance since the average waiting time is higher as compare to other scheduling algorithms.

### Example
Let's take an example of The FCFS scheduling algorithm. In the Following schedule, there are 5 processes with process ID P0, P1, P2, P3 and P4. P0 arrives at time 0, P1 at time 1, P2 at time 2, P3 arrives at time 3 and Process P4 arrives at time 4 in the ready queue. The processes and their respective Arrival and Burst time are given in the following table.

The Turnaround time and the waiting time are calculated by using the following formula.

Turn Around Time = Completion Time - Arrival Time   
    Waiting Time = Turnaround time - Burst Time   

The average waiting Time is determined by summing the respective waiting time of all the processes and divided the sum by the total number of processes.

image.png