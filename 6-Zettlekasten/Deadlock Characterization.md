---
Date: 2025-01-10
Time: 21:18
---
Status: [[Completed]] 

Tags:[[Operating systems]],[[CPU Scheduling]],[[Deadlock]]

# Deadlock Characterization

Each process utilizes a resource as follows:
- request
- use
- release

###### Deadlock can arise if following four necessary conditions hold simultaneously.

1. **Mutual Exclusion**: One or more than one resource are non-shareable means Only one process can use at a time.
2. **Hold and Wait**: A process is holding at least one resource and waiting for another resources.
3. **No Preemption**: A resource cannot be taken from a process unless the process releases the resource means the process which once scheduled will be executed till the completion and no other process can be scheduled by the scheduler meanwhile.
4. **Circular Wait**: A set of processes are waiting for each other in circular form means All the processes must be waiting for the resources in a cyclic manner so that the last process is waiting for the resource which is being held by the first process.

# References