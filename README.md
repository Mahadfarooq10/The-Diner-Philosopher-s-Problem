# The-Diner-Philosopher-s-Problem
The dining philosopher’s problem is a classic example in computer science often used to illustrate synchronization issues and solutions in concurrent algorithm design. It illustrates the challenges of avoiding a system state where progress is not possible, a deadlock.

5 processes were created using the Fork() system call and each process represented a philosopher. 
An array of semaphores was used for the chopsticks and a mutex semaphore was used for critical section exclusiveness. 
For the implementation using Fork() system call rather than threads the memory had to be shared in between the processes and semaphores were used for process synchronization.
The semaphores array and mutex were shared in memory for all the 5 processes using memory maps. 
