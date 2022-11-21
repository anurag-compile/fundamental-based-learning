# Scheduling Algorithms
There are various algorithms which are used by the Operating System to schedule the processes on the processor in an efficient way.

## The Purpose of a Scheduling algorithm
1. Maximum CPU utilization

2. Fare allocation of CPU

3. Maximum throughput

4. Minimum turnaround time

5. Minimum waiting time

6. Minimum response time

## There are the following algorithms which can be used to schedule the jobs.

#### 1. First Come First Serve
It is the simplest algorithm to implement. The process with the minimal arrival time will get the CPU first. The lesser the arrival time, the sooner will the process gets the CPU. It is the non-preemptive type of scheduling.

#### 2. Round Robin
In the Round Robin scheduling algorithm, the OS defines a time quantum (slice). All the processes will get executed in the cyclic way. Each of the process will get the CPU for a small amount of time (called time quantum) and then get back to the ready queue to wait for its next turn. It is a preemptive type of scheduling.
Play Videox

#### 3. Shortest Job First
The job with the shortest burst time will get the CPU first. The lesser the burst time, the sooner will the process get the CPU. It is the non-preemptive type of scheduling.

#### 4. Shortest remaining time first
It is the preemptive form of SJF. In this algorithm, the OS schedules the Job according to the remaining time of the execution.

#### 5. Priority based scheduling
In this algorithm, the priority will be assigned to each of the processes. The higher the priority, the sooner will the process get the CPU. If the priority of the two processes is same then they will be scheduled according to their arrival time.

#### 6. Highest Response Ratio Next
In this scheduling Algorithm, the process with highest response ratio will be scheduled next. This reduces the starvation in the system.
