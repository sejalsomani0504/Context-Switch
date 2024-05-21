---------------------------------------------Operating system-----------------------------------------
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
