# Round Robin Scheduling Algorithm

Round Robin scheduling algorithm is one of the most popular scheduling algorithm which can actually be implemented in most of the operating systems. This is the preemptive version of first come first serve scheduling. The Algorithm focuses on Time Sharing. In this algorithm, every process gets executed in a cyclic way. A certain time slice is defined in the system which is called time quantum. Each process present in the ready queue is assigned the CPU for that time quantum, if the execution of the process is completed during that time then the process will terminate else the process will go back to the ready queue and waits for the next turn to complete the execution.

### Advantages

It can be actually implementable in the system because it is not depending on the burst time.

It doesn't suffer from the problem of starvation or convoy effect.

All the jobs get a fare allocation of CPU.

### Disadvantages

The higher the time quantum, the higher the response time in the system.

The lower the time quantum, the higher the context switching overhead in the system.

Deciding a perfect time quantum is really a very difficult task in the system.

