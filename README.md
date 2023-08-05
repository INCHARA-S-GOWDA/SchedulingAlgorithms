# SchedulingAlgorithms
Problem Statement:- Design, develop and implement a C program to simulate the working of Shortest remaining
time first (SRTF) and Round Robin (RR) scheduling algorithms. Experiment with different quantum sizes for RR
algorithm.

Description:- Round Robin (RR): The basic idea behind the Round Robin scheduling algorithm is to treat all processes or threads equally and fairly by providing each of them an equal share of CPU time(time quantum) in a cyclic manner.It is one of the most widely used scheduling algorithms for preemptive multitasking, where the CPU time is divided into small time slices, and each process is allowed to execute for a fixed amount of time before being preempted and replaced by the next process in the queue.

Shortest remaining time first (SRTF): In the SRTF scheduling algorithm, the CPU is allocated to the process with the smallest remaining burst time, i.e., the process that has the least amount of time left to complete its execution. When a new process enters the system or a process with a shorter burst time becomes available, it can preempt the currently executing process, even if it hasn't finished its entire time slice.
