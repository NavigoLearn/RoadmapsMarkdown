# Linux Roadmap

> **Note:** This roadmap is a work in progress. 
> It contains just the TOC for now.

## Description

This is a roadmap that gives an overview of the key concepts and technologies
you need to know to effectively use Linux. It will help you grasp the essentials
of operating system internals, command-line usage, system administration tasks,
and more.

> **Note:** This roadmap is primarily focused on systems utilizing `systemd`. If
> you want to use a Linux distribution that does not utilize `systemd`, certain 
> aspects of this roadmap may not be applicable.

## Table of Contents

1. **Understanding Linux**
    1. What is Linux?
    2. Short History of Linux
        1. Linux Kernel
        2. GNU Project
        3. Linux Distributions
        4. Linux Desktop Environments
    3. Linux Distributions
        1. Debian-based Distributions (e.g., Ubuntu, Debian)
        2. RPM-based Distributions (e.g., Fedora, CentOS)
        3. Others (e.g., Arch Linux, Gentoo)

2. **Basics of the Linux Command Line**
    1. Navigating the File System (cd, ls, pwd)
    2. File Operations (cp, mv, rm)
    3. Viewing File Contents (less, cat, tail, head)
    4. Utilities (grep, awk, sed)

3. **Process Management**
    1. Understanding Process (ps, top, htop)
    2. Process Control (kill, pkill)
        1. Process Priorities and Niceness
        2. Background and Foreground Processes

4. **Package Management**
    1. Debian-based distros (apt-get, dpkg)
    2. Red Hat-based distros (yum, rpm)
    3. Arch Linux distros (pacman)
    4. Source-based distros (Portage in Gentoo)
    5. Comparison of different package managers

5. **File System Architecture**
    1. File System Layout
    2. File Permissions and Ownership
    3. Understanding Inodes
    4. Understanding different File Systems (ext4, XFS, Btrfs etc.)

6. **Working with Text Files**
    1. Text Editors
        1. Vim
        2. Nano
        3. Micro
        4. Emacs
    2. Searching Text Files (grep, ack)
        1. Regular Expressions
        2. grep
            1. Basic Usage
        3. ack
            1. Basic Usage
    3. Text Processing (sed, awk)
        1. sed
            1. Basic Usage
        2. awk
            1. Basic Usage
    4. Text Manipulation (cut, paste, sort, uniq)
    5. Text Formatting (fmt, pr, column)
    6. Text Comparison (diff, comm)
    7. X11/Wayland Clipboard (xclip, wl-clipboard)

7. **Shell Scripting**
    1. Bash Scripting Basics
    2. Scripting languages (Python, Perl, Ruby, Lua, Node.js. etc.) 
    3. Alternative Shells (zsh, fish, nushell)
    4. Shell Variables and Script Arguments
    5. Understanding Shell Script Execution
    6. Control Structures in Bash (if, loops)

8. **Networking**
    1. Networking Tools (ping, ssh, scp, netstat, netcat, curl, wget)
    2. Firewall Basics (iptables, ufw)
    3. Understanding Network Protocols (TCP, UDP, IP)
    4. DNS and DHCP in Linux

9. **Permissions and Privileges**
    1. Sudo and Root User
    2. Changing File Permissions and Ownership
    3. Understanding setuid, setgid and Sticky Bit
    4. Understanding SELinux

10. **User and Group Management**
    1. Adding and Removing Users (useradd/userdel)
    2. Adding and Removing Groups (groupadd/groupdel)
    3. Modifying User and Group Details
    4. Understanding User and Group IDs

11. **Storage**
    1. Hard Drive Partitioning
    2. Mounting and Unmounting Filesystems
    3. Disk Usage Analysis (df, du)

12. **System Monitoring and Performance Tuning**
    1. Memory Usage Monitoring
    2. CPU Usage Monitoring
    3. Network Monitoring

13. **Backup and Recovery**
    1. Data Backup Strategies
    2. Data Recovery Tools
    3. Using Tar for Backup
    4. Understanding Rsync and rsnapshot

14. **Log Management**
    1. System Logs
    2. Log Analysis Tools (logrotate)
    3. Understanding syslog and journalctl

15. **Virtualization**
    1. Introduction to Virtualization (Docker, KVM)
    2. Containerization Basics with Docker
    3. Understanding VMs on Different Hypervisors (KVM, Xen)
    4. Understanding Linux Containers (LXC)

16. **Security**
    1. Basic Linux Security Concepts
    2. Security Tools and Techniques
    3. Understanding iptables and firewalld
    4. Understanding SELinux and AppArmor

17. **Advanced Command Line Usage**
    1. Regular Expressions
    2. Advanced Shell Features

18. **Linux Kernel**
    1. Understanding the Linux Kernel
    2. Compiling the Linux Kernel
    3. Understanding Kernel Modules
    4. Understanding System Calls

19. **Linux Troubleshooting**
    1. Common Linux Issues and Their Fixes
    2. Linux Rescue and Recovery Techniques
    3. Understanding dmesg and journalctl
    4. Troubleshooting Network with ping, traceroute, mtr

## Essential Prerequisites

* Basics of computer science
    * Understanding of operating systems.
    * Basic knowledge of how a computer works (memory, CPU, storage etc.)

## Recommended Prerequisites

* Understanding the functionality and use of a computer's operating system.
* Basic knowledge of command line functionality.
* Knowledge on installing software on a computer system.