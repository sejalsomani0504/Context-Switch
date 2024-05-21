Context Switching involves storing the context or state of a process so that it can be reloaded when required and execution can be resumed from the same point as earlier. Act of switching from one process to another is called a "Context Switch".Typically there are several tasks to perform in a computer system. So if one task requires some I/O operation, you want to initiate the I/O operation and go on to the next task. You will come back to it later. When you return back to a process, you should resume where you left off. For all practical purposes, this process should never know there was a switch, and it should look like this was the only process in the system.---------------------------------------------Operating system-----------------------------------------
------------------------------------------------------Project : Context switching-----------------------------------------------
Language : C

Files:

1) Main.c
	It contains all operations such as process creation, scheduling ,context switch,updating pcb and gui,which is implemented using GTK.

	To compile & run :
	-> gcc `pkg-config gtk+-3.0 --cflags` main.c stack_implementation.c queue_implementation.c -o os `pkg-config gtk+-3.0 --libs`
	->./os

2) stack_implementation.c
	It contains stack implementation for push,pop operations.

3) queue_implementation.c
	It contains queue implementation for enqueue, dequeue operations.

4) process*.txt
	It contains instruction of process.

This code can be run in linux. Only main.c needs to be run.You need to install GTK3.0 to run this.
