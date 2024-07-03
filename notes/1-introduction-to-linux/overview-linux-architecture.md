# Five layers of Linux
![](/images/five-layers-of-linux.png)
The Linux system comprises 5 distinct layers.
* The outermost layer of Linux architecture is the **UI** (or user interface), which allows users to interact with the system using a keyboard or mouse
* The **Application layer** includes _system daemons, shells, user apps, and tools_ used to perform tasks in a Linux system. The applications communicate with the OS to perform tasks.
* The **Operating system** is responsible for jobs that are vital for system stability such as job scheduling and keeping track of time.
* All Linux OS are built on top of the **Linux Kernel**, which performs the most vital lower-level jobs. The kernel is _the core component of the OS_ and is reponsible for managing memory, processing, device drivers, and security.
* The kernal interacts with the **hardware layer**, which includes all the physical or electronic devices in the computer such as CPU, memory (RAM), storage, and input devices. 

# Linux filesystem
The **Linux filesystem** is the _collection of files on your machine_. It includes the files needed to run the machine and applications as well as your own files contanining your work.

The top level of the filesystem is the **root directory**, symbolized by a forward slash `/`. Bellow this is a **tree-like structure** of the directories and files in the system. And the filesystem _assigns appropiate access rights_ to the directories and files.

One of the _key directories_ is `/bin`, which contains user binary files. Binary files contain the code your machine reads to run programs and execute commands. It's called _"slash bin"_ to signify that it exitst directly below the _root directory_.

Other key directories include:
* `/usr`, which contains _user programs_
* `/home`, which is your personal _working directory_ where you should store all your personal files
* `/boot`, which contains your _system boot files_, the instructions vital for system startup
* `/media`, which contains files related to _temporary media_ such as CD or USB drives that are connected to the system.
