2025-01-02 14:39

Status:

Tags:[[Scheduling Algorithms]],[[CPU Scheduling]],[[Operating systems]] 
# SJF

- Process which have the shortest burst time are scheduled first.If two processes have the same bust time, then FCFS is used to break the tie.
- This is a non-preemptive, preemptive scheduling algorithm.
- Best approach to minimize waiting time.
- Easy to implement in Batch systems where required CPU time is known in advance.
- Impossible to implement in interactive systems where required CPU time is not known.The processor should know in advance how much time process will take.
- Preemptive mode of Shortest Job First is called as Shortest Remaining Time First (SRTF).

#### Advantages 

- SRTF is optimal and guarantees the minimum average waiting time.
- It provides a standard for other algorithms since no other algorithm performs better than it.

#### Disadvantages

- It can not be implemented practically since burst time of the processes can not be known in advance.
- It leads to starvation for processes with larger burst time.
- Priorities can not be set for the processes.
- Processes with larger burst time have poor response time.


# References