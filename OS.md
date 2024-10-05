# What is Operating System?
1. Intermediatory – Acts as an intermediary between user & h/w .
2. Resource Manager/Allocator – Operating system controls and coordinates the use of system resources among various application programs in an unbiased fashion.
3. Platform - OS provides platform on which other application programs can be installed, provides the environment within which programs are executed.
                  *Diagram - Abstract view of Computer System
Example: Ubuntu, Mac, Android, Windows, Linux, Tizen, Debian, Chrome, ios

# Goals and Functions of operating system
• Goals are the ultimate destination, but we follow functions to implement goals.
Example: 58 ministries and 93 departments are responsible to run Govt. of India

# Goals of operating system
1. Primary goals (Convenience / user friendly)
2. Secondary goals (Efficiency (Using resources in efficient manner) / Reliability / maintainability)

# Functions of operating system
1. Process Management: Involves handling the creation, scheduling, and termination of processes, which are executing programs.
2. Memory Management: Manages allocation and deallocation of physical and virtual memory spaces to various programs.
3. I/O Device Management: Handles I/O operations of peripheral devices like disks, keyboards, etc., including buffering and caching.
4. File Management: Manages files on storage devices, including their information, naming, permissions, and hierarchy.
5. Network Management: Manages network protocols and functions, enabling the OS to establish network connections and transfer data.
6. Security & Protection: Ensures system protection against unauthorized access and other security threats through authentication, authorization, and encryption.

# Major Components of operating system
1. Kernel
• Central Component: Manages the system's resources and communication between hardware and software.
2. Process Management
• Process Scheduler: Determines the execution of processes.
• Process Control Block (PCB): Contains process details such as process ID, priority, status, etc.
• Concurrency Control: Manages simultaneous execution.
3. Memory Management
• Physical Memory Management: Manages RAM allocation.
• Virtual Memory Management: Simulates additional memory using disk space.
• Memory Allocation: Assigns memory to different processes.
4. File System Management
• File Handling: Manages the creation, deletion, and access of files and directories.
• File Control Block: Stores file attributes and control information.
• Disk Scheduling: Organizes the order of reading or writing to disk.
5. Device Management
• Device Drivers: Interface between the hardware and the operating system.
• I/O Controllers: Manage data transfer to and from peripheral devices.
6. Security and Access Control
• Authentication: Verifies user credentials.
• Authorization: Controls access permissions to files and directories.
• Encryption: Ensures data confidentiality and integrity.
7. User Interface
• Command Line Interface (CLI): Text-based user interaction.
• Graphical User Interface (GUI): Visual, user-friendly interaction with the OS.
8. Networking
• Network Protocols: Rules for communication between devices on a network.
• Network Interface: Manages connection between the computer and the network.

# Batch Operating System
1. Early computers were not interactive device, there user use to prepare a job which consist three parts
    1. Program
    2. Control information
    3. Input data
2. Only one job is given input at a time as there was no memory, computer will take the input then process it and then generate output.
3. Common input/output device were punch card or tape drives. So these devices were very slow, and processor remain ideal most of the time.
4. To speed up the processing job with similar types (for e.g. FORTRAN jobs, COBOL jobs etc. ) were batched together and were run through the processor as a group (batch).
5. In some system grouping is done by the operator while in some systems it is performed by the 'Batch Monitor' resided in the low end of main memory)
6. Then jobs (as a deck of punched cards) are bundled into batches with similar requirement.

# Spooling
Simultaneous peripheral operations online
1. In a computer system input-output devices, such as printers are very slow relative to the
performance of the rest of the system.
2. Spooling is a process in which data is temporarily held in memory or other volatile storage to
be used by a device or a program.
3. The most common implementation of spooling can be found in typical input/output devices such as the keyboard, mouse and printer. For example, in printer spooling, the documents/files that are sent to the printer are first stored in the memory. Once the printer is ready, it fetches the data and prints it.
4. Ever had your mouse or keyboard freeze briefly? We often click around to test if it's working. When it unfreezes, all those stored clicks execute rapidly due to the device's spool.

# Multiprogramming Operating System
• Multiple Jobs: Keeps several jobs in main memory simultaneously, allowing more efficient utilization of the CPU.
• Job Execution: The OS picks and begins to execute one of the jobs in memory.
• Waiting Jobs: Eventually, a job may need to wait for a task, such as an I/O operation, to complete.
Processor वकसी केविए wait नही ींकरेगा
• Non-Multiprogrammed: CPU sits idle while waiting for a job to complete.
• Multiprogrammed: The OS switches to and executes another job if the current job needs to wait, utilizing the CPU effectively.
Conclusion: show must go on
• Efficient Utilization: Ensures that the CPU is never idle as long as at least one job needs to execute, leading to better utilization of resources.
Advantages:
• High CPU Utilization: Enhances processing efficiency.
• Less Waiting Time: Minimizes idle time.
• Multi-Task Handling: Manages concurrent tasks effectively.
• Shared CPU Time: Increases system efficiency.
Disadvantages:
• Complex Scheduling: Difficult to program.
• Complex Memory Management: Intricate handling of memory is required.

# Multitasking Operating system/time sharing/Multiprogramming with Round Robin/ Fair Share
1. Time sharing (or multitasking) is a logical extension of multiprogramming, it allows many users to share the computer simultaneously. the CPU executes multiple jobs (May belong to different user) by switching among them, but the switches occur so frequently that, each user is given the impression that the entire computer system is dedicated to his/her use, even though it is being shared among many users.
2. In the modern operating systems, we are able to play MP3 music, edit documents in Microsoft Word, surf the Google Chrome all running at the same time. (by context switching, the illusion of parallelism is achieved)
3. For multitasking to take place, firstly there should be multiprogramming i.e. presence of multiple programs ready for execution. And secondly the concept of time sharing.

# Multiprocessing Operating System/ tightly coupled system
1. Multiprocessor Operating System refers to the use of two or more central processing units (CPU) within a single computer system. These multiple CPU’s share system bus, memory and other peripheral devices.
2. Multiple concurrent processes each can run on a separate CPU, here we achieve a true parallel execution of processes.
3. Becomes most important in computer system, where the complexity of the job is more, and CPU divides and conquers the jobs. Generally used in the fields like artificial intelligence and expert system, image processing, weather forecasting etc.

