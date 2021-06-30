<h1> Multiprogramming Operating system </h1>
Sharing the processor, when two or more programs reside in memory at the same time, is referred as multiprogramming. 
Multiprogramming assumes a single shared processor. Multiprogramming increases CPU utilization by organizing jobs 
so that the CPU always has one to execute.

An OS does the following activities related to multiprogramming.
The operating system keeps several jobs in memory at a time.
This set of jobs is a subset of the jobs kept in the job pool.
The operating system picks and begins to execute one of the jobs in the memory.
Multiprogramming operating systems monitor the state of all active programs and 
system resources using memory management programs to ensures that the CPU is never idle, 
unless there are no jobs to process.

Advantages
High and efficient CPU utilization.
User feels that many programs are allotted CPU almost simultaneously.

Disadvantages
CPU scheduling is required.
To accommodate many jobs in memory, memory management is required.
