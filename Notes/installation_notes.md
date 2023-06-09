### Q1: What is virtualization?

Virtualization refers to the process of creating a virtual version of a physical resource, such as a server, operating system, storage device, or network using software

The Virtualization process involves installing a virtualization software or hypervisor on the physical host machine which creates a layer between the hardware and the virtual machines. The hypervisor allows multiple virtual machines to run simultaneously on the same physical hardware

Virtualization has numerous benefits, including:

1. **Cost savings:** Virtualization allows you to run multiple virtual machines on a single physical server, reducing the need for additional hardware and associated costs.
2. **Improved efficiency:** Virtualization enables better utilization of server resources, which can lead to increased productivity and efficiency.
3. **Flexibility:** Virtualization allows you to easily move virtual machines between physical servers, enabling flexibility in resource allocation and workload management.
4. **Improved disaster recovery:** With virtualization, you can easily back up and restore virtual machines, which can simplify disaster recovery and reduce downtime.
5. **Security:** Virtualization can improve security by enabling you to isolate virtual machines from each other, reducing the risk of malware and other security threats.
6. **Testing and development:** Virtualization enables you to create test environments quickly and easily, without the need for additional hardware, allowing for efficient software testing and development.

### Q2: What is VirtualBox :

A free and open-source virtualization program it allows you to run multiple virtual machines on a single physical computer

### Q3: System administration in Linux?

System administration in Linux involves managing and maintaining a Linux-based operating system, including tasks such as user management, system backup and recovery, software installation and upgrades, network configuration, and security management. System administrators work with various tools and utilities to configure, monitor, and troubleshoot the system, and they must have a good understanding of Linux concepts and command-line tools.

### Q4: what is an operating system?

An operating system, or OS, is a software program that manages computer hardware and software resources and provides common services for computer programs. It acts as an intermediary between computer applications and the hardware components of a computer system. The operating system is responsible for tasks such as managing computer memory, scheduling tasks, controlling input and output devices, and facilitating communication between applications.

### Q5: what is Debian?
Debian is a popular Linux-based operating system that is known for its stability, security, and open-source nature. It is widely used in web servers, desktop computers, and many other applications due to its vast software repositories and ease of use.

There are several reasons why you might choose Debian as your operating system, such as:

1. **Stability:** Debian is known for its rock-solid stability and reliability. Its release cycle is more conservative compared to other Linux distributions, which ensures that updates are thoroughly tested before they are released to the public.
2. **Security:** Debian takes security seriously and includes several security features, such as SELinux and AppArmor, to help protect your system from potential threats. Additionally, Debian provides frequent security updates to patch any vulnerabilities that are discovered.
3. **Open-source nature:** Debian is completely open-source, meaning that you have access to the source code and can modify and distribute it as you see fit. This makes it a popular choice for developers and other tech enthusiasts.

### Q6: What is SELinux and AppArmor?

**SELinux** and **AppArmor** are two different security frameworks available in Debian and other Linux distributions that are designed to enhance the security of the system by restricting the actions of processes and applications.

- **SELinux (Security-Enhanced Linux)** is a security mechanism that provides mandatory access control (MAC) to the Linux kernel. It enforces access control policies that define which processes and users can access various system resources. SELinux policies are highly customizable and can provide fine-grained control over system security.

- **AppArmor** is a security module that provides a similar function to SELinux, but with a different approach. It works by defining security profiles for individual applications, which restrict their access to specific system resources. This approach makes it easier to create and maintain security policies for specific applications and reduces the risk of unintended consequences from system-wide policies

### Q7: SELinux vs. AppArmor:
**SELinux (Security-Enhanced Linux)** and **AppArmor** are both security modules used in Linux systems to provide mandatory access control (MAC) for processes and files.
The main difference between SELinux and AppArmor is that SELinux is a more comprehensive security solution, while AppArmor is easier to set up and manage. SELinux has a larger set of rules and policies and is generally better suited for larger and more complex systems, while AppArmor is more suited for simpler systems or for specific applications that require strict security policies.

### Q8: What is a primary partition? 

The primary partition is a type of hard disk partition that can contain both an operating system and user data.

This is the only partition type that can be set active the BIOS on a system can only detect this type of partition and you can only from this primary partition.

### Q9: What is an extended partition?

An extended partition that can be divided into several partitions called logical partitions, you don’t need to assign letters and install a file system. it acts as a container for logical partitions on a system.

### Q10: What is a logical partition?

Logical disk partitions are no different from other types in terms of use and function how ever you cannot boot an operating system from a logical partition. One or more logical partitions can be contained in an extended partition.

Generally. logical partitions are created to organize data on a computer this includes media files, document files, etc.

### Q11: What does encrypted logical volume do?

Logical volume (LV) encryption protects data exposure because of lost or stolen hard disk

drives or because of inappropriately decommissioned computers. the base operating system performs (LV) data encryption and decryption during I/O operations

### Q12: What is the use of a logical volume manager in Linux?

LVM is used for the following purpose: Creating single logical volumes of multiple physical volumes or entire hard disk

Logical volumes are groups of information located on physical volumes. A hierarchy of structures is used to manage disk storage. Each individual disk drive, Called a physical volume (PV) has a name. such as /dev/hddisk0. Every physical volume in use belongs to a volume group (VG)

### Q13: What is the Linux File System?
Linux file system is generally a built-in layer of a Linux operating system used to handle the data management of the storage. It helps to arrange the file on disk storage. It manages the file name, file size, creation date, and much more information about a file.

### Q14: Types of Linux File System

When we install the Linux operating system, Linux offers many file systems such as **Ext, Ext2, Ext3, Ext4, JFS, ReiserFS, XFS, btrfs,** and **swap**.

Ext, Ext2, Ext3 and Ext4 file system

The file system Ext stands for **Extended File System**. The Ext file system is an older version, and is no longer used due to some limitations.

**Ext2** is the first Linux file system that allows managing two terabytes of data. Ext3 is developed through Ext2; it is an upgraded version of Ext2 and contains backward compatibility. The major drawback of Ext3 is that it does not support servers because this file system does not support file recovery and disk snapshots.

**Ext4** file system is the faster file system among all the Ext file systems. It is a very compatible option for the SSD (solid-state drive) disks, and it is the default file system in Linux distribution.

### Q15: Swap File System

Swap Space in Linux is used when the amount of physical memory (RAM) is full. Inactive pages in memory are moved to the swap space. while swap space can help machines with a small amount of RAM.

### Q16: What is journaling in Linux?

A journaling file system is a file system that keeps track of changes not yet committed to the file system’s main part by recording the goal of such changes in a data structure known as a journal which is usually a circular log

The journal allows a file system to instantly recover to the last good state after a system crash

### Q17: What is A mount point in Linux? 

A mount point is a directory on a file system that is logically linked to another file system. Mount points are used to make the data on a different physical storage drive easily available in a folder structure.
