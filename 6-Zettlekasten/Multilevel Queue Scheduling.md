2025-01-04 13:41

Status: #completed

Tags:[[Scheduling Algorithms]],[[Operating systems]],[[CPU Scheduling]]

# Multilevel Queue Scheduling
A multi-level queue scheduling algorithm partitions the ready queue into several separate
queues. The processes are permanently assigned to one queue, generally based on some
property of the process, such as memory size, process priority, or process type. Each queue has
its own scheduling algorithm.
Let us consider an example of a multilevel queue-scheduling algorithm with five queues:
1. System Processes
2. Interactive Processes
3. Interactive Editing Processes
4. Batch Processes
5. Student Processes
Each queue has absolute priority over lower-priority queues. No process in the batch queue,
for example, could run unless the queues for system processes, interactive processes, and
interactive editing processes were all empty. If an interactive editing process entered the ready
queue while a batch process was running, the batch process will be preempted.

![[Pasted image 20250104134502.png]]

# References
