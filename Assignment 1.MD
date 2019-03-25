#  HND in Cyber Security


# Computer-Systems-Architecture


# Assignment 1 


# Humza Ahmed


**Task 1** 

![Poster](https://i.imgur.com/HrPz14v.png)

# The subsystems of a computer 

There are many components that form together to make a computer. Each component has a particular task that it is required to do to run the computer.


**Central processing unit**: 

The CPU does most of the work inside the computer. This component dictates instructions and data flow to and from other areas of the computer. CPU has 2 components control unit and the arithmetic logic unit.


**Memory**:

The main reason for memory is to keep a record of information. There are two main chips which make up the internal memory of a computer. RAM (random access memory) and ROM (read only memory). When a program has been accomplished, the commands are read from the machine code disk file into memory. The program is a pattern of commands stored in memory.


**Input/Output (I/O)**: 

These are devices that talk to the outside world. Some are directly connected with the user, for example keyboards, mouse, a screen. While others are machine readable, a program can read a file from the network.


**Bus**: 

The bus is a link between all the components. It acts as a communication pathway which has a protocol stating exactly how the pathway should be used.

# Memory hierarchy and Storage systems

The memory hierarchy is list of storage systems which is placed in a pyramid like table.  The storage systems are put in order of response time, whereby the fastest is at the top and slowest at the bottom.

# Von Neumann Architecture 

This architecture was first created in 1945. This is a design for a stored program computer which was created by John von Neumann. The design consists of a central processing unit, this has a control unit, arithmetic/logic unit and registers. The design also has a memory unit and input and output.  The control unit handles the workings in the ALU, memory and input/output. It informs these components on how to react to what the instructions are.  The registers are just a place where the data can be stored.


# Basic input/output system 
The Bios is a chip which is placed on a motherboard. This is a piece of hardware which allows the user to find and set up the computer’s system. 
The main functions of the BIOS are: 

**Post** - this something called the power on self-test.  The hardware is assessed here and it checks to see that there are no bugs or errors, after the operating system will load.

**Bootstrap Loader** - This finds the operating system and then the bios will pass control to it. 

**Bios drivers** - Drivers that allow the computer to handle the hardware 

**Bios or Cmos set-up** - this is a program which allows configuration of things like passwords, date and time

**Task 2**

![1](https://i.imgur.com/h7J1Xto.png)
![2](https://i.imgur.com/3vtLAKe.png)
![3](https://i.imgur.com/RbYh2Ow.png)
![4](https://i.imgur.com/n0CtM4i.png)
![5](https://i.imgur.com/nssGeoJ.png)
![6](https://i.imgur.com/4vWqsW5.png)
![7](https://i.imgur.com/XS01hkY.png)






**Task 3**

# Review of task 2 


For task 2 a program was created to make a set of traffic lights, light up in the right order and light up at the right time. Binary code was used to tell which colour to light up in that moment. The simulator used an eight bit CPU which had 256 bytes of RAM. This has a major effect on the performance on the program. For this program the architecture of the CPU was capable to process the speed of this program, however for a more complex program an eight bit program will not be appropriate. The CPU is dependent on how on fast the RAM  is. In this case it had 256 bytes which made this system very slow. 


**Fetch-Decode-Execute Cycle**


This is a process where the computer obtains a program instruction from its memory, then it finds out what sort of actions the instructions is asking for, lastly it performs the action. This cycle happens again and again by the CPU from the boot up and stops when the computer has shut down.

Fetch

Firstly, the CPU retrieves some data and instructions, for example programs, from the main memory and holds them in registers. These registers where the information is stored in, are the CPU's temporary memory areas. The CPU uses something called an address bus. All this is, is a hardware path to the main memory. The CPU will look at the next item and it will store its address on the address bus. Then there is another hardware path known as the data bus. Here the data from the address will move from the main memory to the CPU.

Decode

The CPU is made to recognize a certain set of commands. These are known as the instruction set of the CPU. Different makes of the CPU have a different instruction set. The CPU will decode the information received and prepare many areas within the chip. This is to make it ready for the next step.

Execute 

In this section of the cycle the data will be processed. The instruction is taken place upon the data. The result of the process will be placed in another register. When this stage is complete, the CPU will begin another cycle.


This cycle can be related to my traffic lights simulator. Firstly, some data will be recieved, this is the hexadecimal number. it will then store it and decode it into binary form and then execute it into the traffic light.

![screenshot](https://i.imgur.com/3vtLAKe.png)




# Interrupt 
This is a signal from a device which can be generated from hardware, hardware interrupt or a program, which is known as software interrupt. It asks the operating system to stop and find out what the next step is. Most computers are interrupt driven, meaning a computer will start with a list of instructions and will keep going until either it can’t go further anymore or the interrupt signal is noticed. After the interrupt signal is noticed, two things can happen, the current program will continue to run or a new program will start running. Interrupt can also be used for multitasking. A computer can carry out one task at a time. However, by using an interrupt the computer can share the set of instructions. This gives the ability to the user to do multiple things at the same time. An interrupt handler is some code which is integrated into the operating system. This gives priority to certain interrupts and puts them in a queue.


# Branching 
The CPU will hold a record for the instruction which comes after to be completed in the instruction pointer. The instruction pointer is incremented to identify the following instruction sequentially. The command given to the branch will examine if a particular register is 0 or if a flag is set. If it is the pointer will change to a different address. Hence, the next command will be from another part of the program. 


# Arithmetic logic unit (ALU)
The Arithmetic logic unit is the main part of how the CPU works. The running of the CPU is mostly executed by one or multiple ALU’s. They receive data from input registers. The register is just used as storage. The control unit informs the ALU what work needs to be done on that data. The ALU will then keep the result in an output register. ALU performs basic arithmetic and logic operations. The arithmetic operations are addition, subtraction, multiplication and division. The logic operations are things like NOT, AND, OR.

