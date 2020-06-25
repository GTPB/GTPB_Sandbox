# IBT2020 FAQ

Query:	Are the Linux and Windows Operating Systems compatible?

Reply:	These two Operating Systems are not really compatible, as they manage and explore the hardware differently and use incompatible mechanisms to host applications. In other words you cannot expect to move around seamlessly. Specifically, software developed and installed in one system will not necessarily just run it in the other. A variety of workarounds do exist to reduce the impact of this incompatibility, however, generally at the expense of resources such as memory and disk space, resulting in significantly reduced program execution speeds.

Query:	Can I install both Linux AND Windows on the same machine?

Reply:	Yes, just not one on top of the other. And in general terms it only requires free software and some labour.
    • If you have a comfortable amount of memory and disk space, from either Linux or Windows, you can use a technique called Virtualisation, which involves installing a Virtual Machine (VM) that runs the alternative Operating system. Virtual machines (VMs) are managed by specialised software such as Oracle VM Virtualbox. It is a good idea to have a shared disk area, such as the Downloads folder. This solution may slow down things, and you may be encouraged to add memory to your computer. The two operating systems will be sharing hardware resources all the time.
    • A technique called Containerisation also virtualises a machine with a different Operating System. A container carries the Operating System, installed applications and data, and can be moved around seamlessly in heterogeneous systems. The most commonly used software to do this is Docker. The containers do not run autonomously as VMs, they share software resources with the native Operating System that hosts them.
    • Alternatively, you can create a separate Disk Partition and install the second Operating System there. In this case they will not be running simultaneously, and as you will be starting one OS or the other (so, to change Operating Systems for always involve a reboot of the entire machine), this technique is called “Dual Boot”. Sharing files between the systems is a bit harder to set-up.

Query:	What is Cygwin?

Reply:	Cygwin is just a collection of open source tools that operate in a Linux-like Terminal under MS Windows. You should not expect native Linux applications to run under Cygwin. Its usage is limited to trivial Command Line file manipulations. Cygwin is not suitable for most serious Bioinformatics work.

