# Computer-Systems-Architecture

# Fetch-Decode-Execute Cycle 
This is a process where the computer obtains a program instruction from its memory, then it finds out what sort of actions the instructions is asking for, lastly it performs the action. This cycle happens again and again by the CPU from the boot up and stops when the computer has shut down.

Fetch

Firstly, the CPU retrieves some data and instructions, for example programs, from the main memory and holds them in registers. These registers where the information is stored in, are the CPU's temporary memory areas. The CPU uses something called an address bus. All this is, is a hardware path to the main memory. The CPU will look at the next item and it will store its address on the address bus. Then there is another hardware path known as the data bus. Here the data from the address will move from the main memory to the CPU.

Decode

The CPU is made to recognize a certain set of commands. These are known as the instruction set of the CPU. Different makes of the CPU have a different instruction set. The CPU will decode the information received and prepare many areas within the chip. This is to make it ready for the next step.

Execute 

In this section of the cycle the data will be processed. The instruction is taken place upon the data. The result of the process will be placed in another register. When this stage is complete, the CPU will begin another cycle.



# Interrupt 
This is a signal from a device which can be generated from hardware, hardware interrupt or a program, which is known as software interrupt. It asks the operating system to stop and find out what the next step is. Most computers are interrupt driven, meaning a computer will start with a list of instructions and will keep going until either it can’t go further anymore or the interrupt signal is noticed. After the interrupt signal is noticed, two things can happen, the current program will continue to run or a new program will start running. Interrupt can also be used for multitasking. A computer can carry out one task at a time. However, by using an interrupt the computer can share the set of instructions. This gives the ability to the user to do multiple things at the same time. An interrupt handler is some code which is integrated into the operating system. This gives priority to certain interrupts and puts them in a queue.


# Branching 
The CPU will hold a record for the instruction which comes after to be completed in the instruction pointer. The instruction pointer is incremented to identify the following instruction sequentially. The command given to the branch will examine if a particular register is 0 or if a flag is set. If it is the pointer will change to a different address. Hence, the next command will be from another part of the program. 


# Arithmetic logic unit (ALU)
The Arithmetic logic unit is the main part of how the CPU works. The running of the CPU is mostly executed by one or multiple ALU’s. They receive data from input registers. The register is just used as storage. The control unit informs the ALU what work needs to be done on that data. The ALU will then keep the result in an output register. ALU performs basic arithmetic and logic operations. The arithmetic operations are addition, subtraction, multiplication and division. The logic operations are things like NOT, AND, OR.

