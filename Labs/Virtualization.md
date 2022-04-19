# Virtualization

## Objectives

- Overview of virtualization
- Installation of [Oracle Virtualbox](https://www.virtualbox.org/) hypervisor
- Installation of [Fedora Linux](https://getfedora.org/) as the guest operating system

## What is virtualization

[Virtualization](https://en.wikipedia.org/wiki/Virtualization) is the act of creating a virtual (rather than actual) version of something, including virtual computer hardware platforms, storage devices, and computer network resources.

A piece of software is required to create virtual machines (guest machines) on the physical hardware (host machine).  This piece of software is known as the hypervisor or virtual machine monitor.

## Hypervisors

There are 2 types of hypervisor.

- Type 1: Run directly on the host's hardware, eg Linux KVM, VMware ESXi
- Type 2: Run on top of another operating system, eg Oracle Virtualbox, VMware Workstation Player

## Lab

1 > [Download Oracle Virtualbox](https://www.virtualbox.org/) - Choose the appropriate version for your OS

2 > [Download Fedora Linux](https://getfedora.org/en/workstation/download/) - Get the latest stable version available.

3 > [Install Virtualbox](https://www.virtualbox.org/manual/ch01.html#intro-installing) - Follow the user manual to install Oracle Virtualbox

4 > [Start Virtualbox](https://www.virtualbox.org/manual/ch01.html#intro-starting)

5 > [Creating a new Virtual Machine in Virtualbox](https://www.virtualbox.org/manual/ch01.html#gui-createvm) - Note the following:

1. Name: Fedora
2. Type: Linux
3. Hard Disk: 15 GB, dynamically allocated
4. Memory: 2 GB
5. Mount the Fedora Linux ISO as a DVD in the VM created

6 > [Start VM](https://www.virtualbox.org/manual/ch01.html#intro-starting-vm-first-time) and [Install Fedora Linux](https://docs.fedoraproject.org/en-US/fedora/latest/install-guide/install/Installing_Using_Anaconda/#sect-installation-graphical-mode)

## Resources

- [Wikipedia: Virtualization](https://en.wikipedia.org/wiki/Virtualization)
- [Redhat article: What is virtualization](https://www.redhat.com/en/topics/virtualization)
- [Oracle Virtualbox Documentation](https://www.virtualbox.org/wiki/End-user_documentation)
