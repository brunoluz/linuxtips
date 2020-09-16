# Process Types

|Process Type|Description|Example|
|-|-|-|
|Interactive Processes|Need to be started by a user, either at a command line or through a graphical interface such as an icon or a menu selection|bash, firefox, top|
|Batch Processes|Automatic processes which are scheduled from and then disconnected from the terminal. These tasks are queued and work on a FIFO (First-In, First-Out) basis|updatedb, ldconfig|
|Daemons|Server processes that run continuously. Many are launched during system startup and then wait for a user or system request indicating that their service is required|httpd, sshd, libvirtd|
|Threads|Lightweight processes. These are tasks that run under the umbrella of a main process, sharing memory and other resources, but are scheduled and run by the system on an individual basis. An individual thread can end without terminating the whole process and a process can create new threads at any time. Many non-trivial programs are multi-threaded|firefox, gnome-terminal-server|
|Kernel Threads|Kernel tasks that users neither start nor terminate and have little control over. These may perform actions like moving a thread from one CPU to another, or making sure input/output operations to disk are completed|kthreadd, migration, ksoftirqd|

PID = Process ID

# PID Types
|ID Type|Description|
|-|-|
|Process ID (PID)|Unique Process ID number|
|Parent Process ID (PPID)|Process (Parent) that started this process. If the parent dies, the PPID will refer to an adoptive parent; on recent kernels, this is kthreadd which has PPID=2|
|Thread ID (TID)|Thread ID number. This is the same as the PID for single-threaded processes. For a multi-threaded process, each thread shares the same PID, but has a unique TID|