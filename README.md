# multiLevelFeedBack
Implementation of multilevel feedback queuing system
Programming Language I used is - c++
Assumptions:
1. Implemented three queue's namely Q0,Q1 and Q2
2. Q0 is Round Robin with quantum 8, Q1 is Round Robin with quantum 16 and Q2 is FCFS
3. Each process has a Data Structure and each process has arrival time, burst time, Waiting time, Completion Time, Turn around time and Response Time
4. The Arrival Time and Burst Time are generated using a random number generator.
5. If the process is not completed in q0 it is moved to q1 though it is not completed in q2 where it is served FCFS.

Limitations:
1. User can create a maximum of 20 processes.

Known Bugs:
There are no known bugs.

Results:
The project works as expected.
