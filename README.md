# Multilevel-Feedback-Queue-Type 1
The concept of Multilevel Feedback Queue is implemented using java. The execution time is shown by sleep() method provided by the Thread class.This Scheduling is like Multilevel Queue(MLQ) Scheduling but in this process can move between the queues. Multilevel Feedback Queue Scheduling (MLFQ) keep analyzing the behavior (time of execution) of processes and according to which it changes its priority. For further refrence use the link: https://www.geeksforgeeks.org/multilevel-feedback-queue-scheduling-mlfq-cpu-scheduling/ 
Here the concept is shown using 4 Queues.
Queue 1, Queue 2 and Queue 3 follows Round Robin algorithm and Queue 4 follows FCFS.
The algorithm is strictly followed.

# Points to be Noted

It does not include the solution of the problem of starvation.
The time slice are 2, 4 and 6 respectively.
