# Introduction: 
A computer can be divided into two main parts, the hardware and the software. The hardware consist of all the physical devices present in our computer such as hard disk, CPU, memory, registers and so on. The software on the other hand, consist of the Kernel, system calls, application programs, bootloader, shells and you name the rest. Both these hardware and software will not produce any output if they are not well controlled and organized. This is where the operating system comes into play. It is a software, which manages all these resources and serves as an interface between the user and its computer.  
# Purpose: 

The main purpose behind this project is for us to know how the operating system manages all the activities in our computer and try to come out with a similar implementation. 
Having in mind that there are many types of Operating Systems (Networking, distributed, Mobile, multiprocessing etc.), we focused on an operating system with the following characteristics: <br>
###	Multiprogramming: i.e. multiple programs can be executed concurrently. This is to avoid the computer from being dormant <br>
### Multitasking/time sharing: i.e. possibility for multithreading and can manage more than one user. Considering the fact that multithreading is faster and safer than multiprocessing <br>
###	Symmetric: i.e. all the processes can be executed both concurrently and in parallel depending on the number of cores. With no process being a master process and the others being slave processes <br>
To what concerns the structure of our Operating system, we when in for a UNIX based kernel called monolithic kernel, in which we put most of our programs such as the ones involved in file management, process synchronization, CPU scheduling etc. 
One benefit of this structure is that, it prevents the application programs from directly interacting with the hardware. However, the disadvantage is that, if one error occurs in the kernel, all the programs found inside would be affected. 

### Objectives: 
Following a UNIX based operating system, our objective is to design an operating system which is at a  
### User point of view, convenient to use, easy to learn, reliable, safe and fast. And in the  
### Developers’ point of view, it should be easy to design, implement and maintain, flexible, reliable, error-free and efficient.  
To achieve this, we decided to build a simple operating system, which provides a nice looking Graphical User Interface (GUI) and Command Line Interface (CLI), permits users to create, rename, update, copy or delete a file. Change background and text color, authorize access to certain files only to the Super User (the Admin) and displays the time and date. Services provided: <br>
Here is an overview of the services provided by our Operating system: <br>
	A user Interface <br>
	Program execution <br>
	Input/output operations <br> 
	File system management <br>
	Inter process communication <br>
	Error detection <br>
	Resource allocation <br>
	Accounting <br>
	Protection and security <br>

 
 

