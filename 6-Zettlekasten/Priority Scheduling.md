2025-01-02 14:41

Status:

Tags:[[Scheduling Algorithms]],[[Operating systems]],[[CPU Scheduling]] 

# Priority Scheduling

- Out of all the available processes, CPU is assigned to the process having the highest priority.
- In case of a tie, it is broken by FCFS Scheduling.
- Priority Scheduling can be used in both preemptive and non-preemptive mode.
- The waiting time for the process having the highest priority will always be zero in preemptive mode.
- The waiting time for the process having the highest priority may not be zero in non-preemptive mode.

###### Priority scheduling in preemptive and non-preemptive mode behaves exactly same under following conditions-
- The arrival time of all the processes is same.
- All the processes become available
#### Advantages 

- It considers the priority of the processes and allows the important processes to run first.
- Priority scheduling in preemptive mode is best suited for real time operating system.
#### Disadvantages

- Processes with lesser priority may starve for CPU.
- There is no idea of response time and waiting time.

#### Example

![[Pasted image 20250104130543.png]]

# References