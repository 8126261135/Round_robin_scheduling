# Round_robin_scheduling
We first have a queue where the processes are arranged in first come first serve order.
A quantum value is allocated to execute each process.
The first process is executed until the end of the quantum value. After this, an interrupt is generated and the state is saved.
The CPU then moves to the next process and the same method is followed.
Same steps are repeated till all the processes are over.
