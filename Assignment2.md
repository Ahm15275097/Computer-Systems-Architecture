# Operating Systems

In this report I will be going through a few operating systems, why they are useful and what the purpose of these operating system's are. In this report we will also be looking at the key features of the operating system and how the choice of the operating system affects the hardware and software requirements for the client. The two operating system's that will be compared in this report are Windows 10 and Mac OS X.


On July 29, 2015 Microsoft released a brand new operating system, this was Windows 10. This is part of the Windows NT family of operating system and is a successor to windows 8.1. Windows 10 is a closed source operating system, this means the source code is not accessble to the public, they cannot see it or make changes to it. 

** Windows OS kernel**


A computer program known as kernel is the main part of the the computer's operating system. The kernel has full control over everything in the system. Usually, after the bootloader this is one of the first programs to be loaded. It controls the rest of the start-up and also receives information from input and output, turning them into data-processing instructions for the CPU.

Windows 10 has a kernel type which is hybrid, this means it tries to have aspects and good features of both microkernel and monolithic kernel architectures. 

A microkernel is the near-minimum amount of software that can supply the mechanisms required to implement an operating system (OS). The mechanisms take into account low-level address space management, thread management, and inter-process communication (IPC). A monolithic kernel A monolithic kernel is an operating system architecture where the entire operating system is working in kernel space. The monolithic model differs from other operating system architectures (such as the microkernel architecture)[1][2] in that it alone defines a high-level virtual interface over computer hardware

The OS architecture known as monolithic kernel is where the whole operating system is operating in kernel space. This is different to architectures such as microkernel in that only it alone characterises a high-level virtual interface over PC equipment. 

**Application programming interface**

An application program interface (API) is an arrangement of schedules, conventions, and devices for building programming applications. An API determines how programming parts should talk to each other. Furthermore, APIs are utilised when programming GUI parts.


The windows API allows the capability to develop applications that run effectively on all forms of windows while making use of the features and abilities that are different to each version.This API can be utilised in all windows based applications, and the similar capabilities are available on 32-bit and 64-bit windows. The way they are integrated are different depending on the specification of the operating system.


**File system**

NTFS (New Technology File System) is the file system that windows 10 uses, it is used for holding and retrieving files which are on the hard disk. It's performance, extendability and security is a much more improved system than the file allocation table (FAT) which was used on windows 95.


**Memory management**

The way in which memory is handled and coordinated is generally what memory management is. It allocares portions known as blocks to many different running programs to enhance the overall performance of the system. Memory management lives in the hardware, the operating system, and also in programs and applications.

Components that physically hold information, for example RAM (random access memory)chips, memory caches, and flash-based SSDs (solid-state drives) are to do with memory management which is in hardware.The assignment and reassignment of particular memory blocks to individual programs as a user requests change. The memory management for applications makes sure that there is enough memory for the objects and data structures of each running program at all times. This type of memory management combines tasks such as allocation and recycling. An allocater will assign a block of memory to the program and when a program doesnt require data anymore the blocks can be used for reallocation.


On a 32-bit system each process has its own virtual address space that allows addressing up to 4 gigabytes of memory. On a 64-bit system each process can have 8 terabytes worth of virtual address space. A process has threads and all these threads can reach its virtual address space. Threads will not be able to get to memory that another process owns, this shields a process from being corrupted by a different process. 

The memory manager integrates virtual memory, gives a main set of services like memory mapped files, copy-on-write memory, large memory support and help for the cache manager.


**User interface**

# Mac OS X

This is an operating which is used for Apple. This is an operating sytem which focusses on modularity so that when changes happen it would be easy to incorporate. OS X integrates support for unix based applications and also those which are written only for macintosh. This operating system was released on the 24th of March 2001, since then many upgrades have taken place. This operating system comes from the family of macintosh, unix and is a closed source model.  

**Mac OS kernel**


The kernel type for this operating system is XNU which has been developed since December 1996. This is a free and open source software. It is written in C or C++ and is a hybrid kernel type, meaning it takes the good features of both monolithic and microkernel architectures.

**Application programming interface**

Apple have developed their very own applicaton programming interface known as Cocoa. This API can be written in C, C++, Objective-C or swift. It is a closed source software but can have some features which are open source. Applications to do with Cocoa are mainly developed using tools that are given by Apple, these are Xcode and Interface Builder. 


**File system**

Apple have their own file system which is known as APFS (Apple File System), it is a closed source file system and designed for newer versions of Apple's operating system. This can be for the High Sierra and later versions, IOS 10.3 and later versions, or even the tvOS 10.2 and later versions. This was designed on March the 27th, 2017 and was made to try and fix the problems that HFS+(MAC OS Extended) had. APFS is made better for flash and solid state drive, with it focussing on encryption.


**Memory management**


**User Interface**



**Hardware requirements**

The client has a choice between choosing Windows 10 or Mac OS X. Here are the different set of hardware requirements for both operating systems. The client would need to meet these requirements so they can have the operating system of their choice.

**Windows 10**
 
 - Processor      :	 1 gigahertz (GHz)
 - RAM            :	 1 gigabyte (GB) for 32-bit or 2 GB for 64-bit
 - Hard disk space:	 16 GB for 32-bit OS 20 GB for 64-bit OS
 - Graphics card  :	 DirectX 9 
 - Display        :	 800x600 pixels 
 
 **Mac OS X (Mac OS X v10.6)**
 - Processor      :  An Intel processor
 - RAM            :  At least 1 GB of RAM (additional RAM is recommended)
 - Graphics card  :  A built-in display or a display connected to an Apple-supplied video card supported by your computer
 - Hard disk space:  Hard at least 5 GB of disk space available, or 7 GB of disk space if you install the developer tools
 
 **Application software requirements**
 
 **Data and system security**

**Windows**

Any operating system that is in use can have a security breach but windows protects the user from being attacked. Microsoft have many features that are integrated into their system to help the user, for example doing windows updates. Microsoft try to make their system as secure as possible when they release it. However, hackers can find weaknesses very quickly and they take advantage by breaking into a network or stealing data. While hackers are finding weaknesses in the system, microsoft are finding ways to repair the issues and help solve the problem. This can be done by the regular updates that microsoft encourage the user to do. Normally, microsoft send out an update as soon as a potential security threat is discovered, this can help the system be protected from threats that could occur.

Another way that Microsoft can help the system from being attacked is by installing Anti-Virus. Stopping viruses/malware and intruders is very important in protecting the data and personal information on the system. Cyber criminals will uses things like viruses and malware to try to get into your computer. An anti-virus has real-time monioring that allows the software to recognize and nulify malicous software before it can install itself and compromise the computer. 

**Mac OS**

Similar to the windows operating system the mac OS allows the user to run the latest software. The OS looks for new updates, so its very easy to continuously have the latest and safest version.

The Mac OS has something called FileVault 2, this makes the information safe and secure. FileVault 2 encrypts the whole drive shielding the data with XTS-AES 128 encryption. On Mac devices that have an Apple Tw chip, Filevault 2 key are created and shielded by secure enclave.

The runtime protections in the system operates at the very heart of the Mac. XD (execute disable), Address Space Layout Randomisation (ASLR) and Kernel ASLR can make it very hard for malware to perform or do harm via memory or other apps. System Integrity Protection (SIP) makes sure that if malware can reach the system, really important changes will not happen to the system.

**Error management**



 
 
 # Networking 
 ![Task 2](https://i.imgur.com/1gcckq4.png)
 
Physical Topologies

The physical topology is the way components are laid out on a network. Generally, all local area networks have a topology, it is the method that the components on a network are arranged and how they interact with each other. It is how the computers are linked to the network through the cables. 


![Physical Topology](https://i.imgur.com/Y5FGXLc.png)

Logical Topologies


The logical topology is the way the information behaves on a network media, it is the way that data is transmitted through the network from one device to another. This doesn’t take into account the physical connection between the devices.

![Logical Topology](https://i.imgur.com/EyiCpzc.jpg)


# OSI model vs TCP/IP model

The Open Systems Interconnection model (OSI model) is a model that specifies the communication functions of a system without it taking into account its internal structure. The target of this model is to exchange and make use of information of various communication system with standard protocols. 



7.  Application layer

6.  Presentation layer

5.  Session layer

4.  Transport layer

3.  Network layer

2.  Data link layer

1.  Physical layer




 
 
 






 
  
  
  
  
 
 
  
  
  
  
 



 
 
 






 
  
  
  
  
 
 
  
  
  
  
 



 
