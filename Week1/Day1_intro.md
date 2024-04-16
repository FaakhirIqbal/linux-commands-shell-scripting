## Day1: Intro. to Unix: An Overview

Unix is an Operating System developed in the 1970s at AT&T Laboratories by Ken Thompson, Dennis Ritchie, and others. It was initially designed for programmers but eventually gained widespread adoption. The Unix kernel was the main focus, serving as the heart of the operating system. Unix and the C programming language were distributed to government and academic institutions, leading to their widespread use across various machine families. Unix is a family of multitasking, multiuser operating systems known for its stability, security, and scalability, making it popular for enterprise-level computing. Its design philosophy emphasizes simple, powerful tools that can be combined for complex tasks, featuring a command-line interface.

### Key Features of Unix

1. Multiuser and multitasking capabilities, allowing multiple users to access the system simultaneously and run multiple processes concurrently.
2. Powerful shell scripting language for automating tasks and combining simple tools to perform complex operations.
3. Robust security model with features like file permissions, user accounts, and network security, combined with portability across a wide range of hardware platforms.


![unix_1](https://github.com/FaakhirIqbal/linux-commands-shell-scripting/assets/12996201/b237e786-d12b-4c42-ac13-b1b47553b2b5)


Unix has three levels: **user**, **kernel**, and **hardware**.

System calls and libraries interface between user programs and the kernel.

File subsystem manages files, allocates space, controls access, and retrieves data.

Processes interact with the file subsystem through specific system calls like open, close, read, write, etc.

Device drivers control peripheral devices, handle interrupts, and communicate with hardware.

