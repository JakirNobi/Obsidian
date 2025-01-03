2025-01-02 14:13

Status:

Tags:[[Operating systems]],[[Scheduling Algorithms]],[[CPU Scheduling]]

# FCFS

In FCFS Scheduling
- The process which arrives first in the ready queue is firstly assigned the CPU.
- In case of a tie, process with smaller process id is executed first.
- It is always non-preemptive in nature.
- Jobs are executed on first come, first serve basis.
- It is a non-preemptive, preemptive scheduling algorithm.
- Easy to understand and implement.
- Its implementation is based on FIFO queue.
- Poor in performance as average wait time is high.

#### Advantages

- It is simple and easy to understand.
- It can be easily implemented using queue data structure.
- It does not lead to starvation.
####  Disadvantages

- It does not consider the priority or burst time of the processes.
- It suffers from convoy effect i.e. processes with higher burst time arrived before the processes with smaller burst time.

![[Pasted Image 20250102145058_290.png]]

# References

