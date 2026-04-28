# OSSP-individual-assignment-Eyob-masresha-RHEL-OS
RHEL Installation and Configuration on Virtual Environments
​This project details the process of safely installing and configuring Red Hat Enterprise Linux (RHEL) inside a virtualized environment. By using virtualization, this guide demonstrates how to test enterprise-grade operating systems without risking the stability of a host machine.  
​Project Overview
​The primary goal of this assignment was to successfully deploy RHEL on a virtual machine (VM) while exploring its enterprise features and system administration fundamentals.  
​Objectives
​Successfully install RHEL using VMware Workstation or Oracle VM VirtualBox.  
​Understand step-by-step procedures including disk partitioning, user creation, and system configuration.  
​Analyze supported file systems such as XFS and ext4.  
​Evaluate the benefits of running enterprise Linux in a virtualized environment.  
​System Requirements
​Hardware Requirements
​To ensure a smooth workstation/GUI experience, the following resources were allocated:  
​RAM: At least 8 GB.  
​Storage: 60 GB of free SSD space (20 GB minimum for the virtual disk).  
​Processor: 64-bit x86_64 (Intel or AMD) with virtualization extensions enabled.  
​Network: Stable internet connection for registration and updates.  
​Software Requirements
​Hypervisor: VMware Workstation Player (Version 17.6.3 used in this project).  
​OS Image: Official RHEL Binary DVD ISO (Version 10.1 used).  
​Subscription: A free Red Hat Developer Subscription for access to repositories and updates.  
​Installation Steps
​Hypervisor Setup: Downloaded and installed VMware Workstation Player from the official site.  
​RHEL ISO Acquisition: Registered for a Red Hat Developer account and downloaded the RHEL 10.1 x86_64 Binary DVD.  
​Virtual Machine Creation:
​Set up a new VM using the "Typical" configuration.  
​Attached the downloaded ISO file as the installer disc.  
​Named the VM and allocated 20 GB of disk capacity.  
​OS Configuration:
​Selected the language and connected the system to the Red Hat account using developer credentials.  
​Configured the installation destination on the 20 GB virtual disk.  
​Created a root-privileged user account.  
​Finalization: Completed the installation progress and rebooted the system to access the GNOME desktop environment.  
​Technical Analysis
​File System Support
​RHEL officially supports the following file systems:  
​XFS: The default and recommended choice for high-performance and large-scale scalability.  
​ext4: A reliable fallback that supports shrinking partitions, ideal for general-purpose use.  
​FAT32: Used primarily for cross-platform data exchange and UEFI boot partitions.  
​Pros and Cons of RHEL
Advantage Disadvantage
Industry Standard: Renowned for rock-solid stability and reliability. Cost: Requires a paid subscription for official commercial support.
Security: Integrated tools like SELinux and kernel live patching. Older Software: Focuses on stability over the latest "bleeding-edge" features.
Automation: Seamless integration with the Ansible Automation Platform. Learning
Conclusion
​The project successfully resulted in a working RHEL desktop environment. This setup provides a safe lab for practicing advanced system administration, security hardening, and enterprise application deployment.  
​This project was completed by Eyob Masresha as part of the OSSP Project Individual Assignment at Bahir Dar University
