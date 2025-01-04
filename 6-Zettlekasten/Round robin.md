2025-01-02 14:41

Status:

Tags:[[CPU Scheduling]],,[[Scheduling Algorithms]],[[Operating systems]] 

# Round robin

- CPU is assigned to the process on the basis of FCFS for a fixed amount of time.
- This fixed amount of time is called as time quantum or time slice.
- After the time quantum expires, the running process is preempted and sent to the ready queue.
- Then, the processor is assigned to the next arrived process.
- It is always preemptive in nature.
#### Algorithm

![[Pasted image 20250104124830.png]]

#### Advantages

- It gives the best performance in terms of average response time.
- It is best suited for time sharing system, client server architecture and interactive system.

#### Disadvantages

- It leads to starvation for processes with larger burst time as they have to repeat the cycle many times.
- Its performance heavily depends on time quantum.
- Priorities can not be set for the processes.

##### With decreasing value of time quantum :
- Number of context switch increases
- Response time decreases
- Chances of starvation decreases
Thus, smaller value of time quantum is better in terms of response time.

##### 
# References