# Highest Response Ratio Next (HRRN) Scheduling

Highest Response Ratio Next (HRNN) is one of the most optimal scheduling algorithms. This is a non-preemptive algorithm in which, the scheduling is done on the basis of an extra parameter called Response Ratio. A Response Ratio is calculated for each of the available jobs and the Job with the highest response ratio is given priority over the others.

Response Ratio is calculated by the given formula.

Response Ratio = (W+S)/S   

Where,

W → Waiting Time   
S → Service Time or Burst Time  

If we look at the formula, we will notice that the job with the shorter burst time will be given priority but it is also including an extra factor called waiting time. Since,

HRNN α W  

            HRNN α (1/S)      

Hence,

This algorithm not only favors shorter job but it also concern the waiting time of the longer jobs.
Its mode is non preemptive hence context switching is minimal in this algorithm.