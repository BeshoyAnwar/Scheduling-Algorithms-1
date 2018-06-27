# Scheduling-Algorithms
## Description
### Why do we need scheduling?
A typical process involves both I/O time and CPU time. In a uniprogramming system like MS-DOS, time spent waiting for I/O is wasted and CPU is free during this time. In multiprogramming systems, one process can use CPU while another is waiting for I/O. This is possible only with process scheduling. 
### Different Scheduling Algorithms
#### First Come First Serve (FCFS)
Simplest scheduling algorithm that schedules according to arrival times of processes.
#### Shortest Job First(SJF)
Process which have the shortest burst time are scheduled first.
#### Shortest Remaining Time First(SRTF)
It is preemptive mode of SJF algorithm in which jobs are schedule according to shortest remaining time.
#### Round Robin Scheduling
Each process is assigned a fixed time in cyclic way.
#### Priority Based scheduling (Non Preemptive)
In this scheduling, processes are scheduled according to their priorities, i.e., highest priority process is schedule first. If priorities of two processes match, then schedule according to arrival time.
#### Priority Based scheduling (Preemptive)
similar to priority(NP) but if a process arrived with higher priority than the process already scheduled on the process, the higer process will take the processor and the other will wait.

## How to run
-Download the [package](https://github.com/BeshoyAnwar/Scheduling-Algorithms-OS/raw/master/SchedulingAlgorithmsProject2018.rar)

-Extract it

-you will find an app with .dxe extension change it to .exe then open it

-you will find folder for screenshots showing the testing process,source code folder & the user guide may help you 
