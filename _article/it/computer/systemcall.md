---
title: System Call
---
A System Call (SysCall) is a method for userspace processes to request a service from the kernel of the operating system.

Common Unix-Like SysCalls: `open`, `read`, `write`, `close`, `wait`, `exec`, `fork`, `exit`, and `kill`.


## Categories
System calls can be roughly grouped into five major categories:

1. Process Control: load, execute, end, create, get/set attributes
1. File management: create, delete, open, close, read, write 
1. Device Management: request, release, read, write
1. Information Access: get/set attributes of process/file/device
1. Communication: open, close, send, receive


## References
Linux SystemCalls: http://syscalls.kernelgrok.com/
