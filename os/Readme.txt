Considering the arrival time and burst time requirement of the process the scheduler schedules the processes 
by interrupting the processor after every 6 units of time and does consider the completion of the process in this
iteration. The scheduler than checks for the number of process waiting for the processor and allots the processor
to the process but interrupting the processor every 10 unit of time and considers the completion of the processes
in this iteration. The scheduler checks the number of processes waiting in the queue for the processor after the 
second iteration and gives the processor to the process which needs more time to complete than the other processes
to go in the terminated state.The inputs for the number of requirements, arrival time and burst time should be 
provided by the user.


         So we need to first place processes according to their burst time in ready queue, for the first iteration
we have to take time quantum 6 units and after process p4 comes at first time, second iteration will start by 
taking a time quantum 10 units, after completion of two iterations.  We need to check the process which had the 
highest burst time and allocate the process to processor, remaining processes will terminate even though if they 
had a burst time