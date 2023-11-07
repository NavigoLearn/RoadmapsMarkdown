# Linux Roadmap

## Description

This is a roadmap that gives an overview of the key concepts and technologies
you need to know to effectively use Linux. It will help you grasp the essentials
of operating system internals, command-line usage, system administration tasks,
and more.

> **Note:** This roadmap is primarily focused on systems utilizing `systemd`. If
> you want to use a Linux distribution that does not utilize `systemd`, certain 
> aspects of this roadmap may not be applicable.

## Table of Contents

1. **[Understanding Linux](/operatingSystems/linux/chapters/understandLinux.md)**
    1. What is Linux?
        1. Bootloader Introduction
        2. Kernel Introduction
        3. Daemons Introduction
        4. Shell Introduction
        5. Graphical Server Introduction
        6. Desktop Environment Introduction
        7. Applications Introduction
    2. Short History of Linux
        1. Linux Kernel
        2. GNU Project
        3. Linux Distributions
        4. Linux Desktop Environments
    3. Linux Distributions
        1. Debian-based Distributions (e.g., Ubuntu, Debian)
        2. RPM-based Distributions (e.g., Fedora, CentOS)
        3. Others (e.g., Arch Linux, Gentoo)
    4. Linux Jargon

2. **[Basics of the Linux Command Line](/operatingSystems/linux/chapters/commandLine.md)**
    1. Navigating the File System (cd, ls, pwd)
    2. File Operations (cp, mv, rm)
    3. Viewing File Contents (less, cat, tail, head)
    4. Utilities (grep, awk, sed, find)

3. **[Process Management](/operatingSystems/linux/chapters/processManagement.md)**
    1. Process Listing and Monitoring (ps, top, htop)
    2. Process Control (kill, pkill)
        1. Process Priorities and Niceness
        2. Background and Foreground Processes

4. **[Package Management](/operatingSystems/linux/chapters/packageManagement.md)**
    1. Debian-based distros (apt-get, dpkg)
    2. Red Hat-based distros (dnf, yum, rpm)
    3. Arch Linux distros (yay, pacman)
    4. Source-based distros (Portage in Gentoo)
    5. Comparison of different package managers

5. **[File System Architecture](/operatingSystems/linux/chapters/fileSystem.md)**
    1. File System Layout
    2. File Permissions and Ownership
    3. Understanding different File Systems (ext4, XFS, Btrfs etc.)

6. **[Working with Text Files](/operatingSystems/linux/chapters/textFiles.md)**
    1. Text Editors
        1. Vim / Vi
        2. Nano
        3. Micro
        4. Emacs
    2. Text Manipulation (cut, paste, sort, uniq)
    3. Text Formatting (fmt, pr, column)
    4. Text Comparison (diff, comm)
    5. X11/Wayland Clipboard (xclip, wl-clipboard)

7. **[Shell Scripting](/operatingSystems/linux/chapters/shellScripting.md)**
    1. Bash Scripting Basics
    2. Scripting languages (Python, Perl, Ruby, Lua, Node.js. etc.) 
    3. Alternative Shells (zsh, fish, nushell)
    4. Cron Jobs

8. **[Networking](/operatingSystems/linux/chapters/networking.md)**
    1. Networking Tools (ping, ssh, scp, netstat, netcat, curl, wget)
    2. Firewall Basics (firewalld, iptables, ufw)
    3. Understanding Network Protocols (TCP, UDP, IP)
    4. DNS and DHCP in Linux

9. **[User and Group Management](/operatingSystems/linux/chapters/usersAndGroups.md)**
    1. Adding and Removing Users (useradd/userdel)
    2. Adding and Removing Groups (groupadd/groupdel)
    3. Modifying User and Group Details
    4. Understanding User and Group IDs

10. **[Permissions and Privileges](/operatingSystems/linux/chapters/priviledges.md)**
    1. Sudo and Root User
    2. Changing File Permissions and Ownership
    3. Understanding setuid, setgid and Sticky Bit
    4. Understanding SELinux

11. **[Storage](/operatingSystems/linux/chapters/storage.md)**
    1. Partitioning
    2. Mounting and Unmounting Filesystems
    3. Disk Usage Analysis (df, du)

12. **[Log Management](/operatingSystems/linux/chapters/logging.md)**
    1. System Logs
    2. Log Analysis Tools (logrotate)
    3. Understanding syslog and journalctl

13. **[Security](/operatingSystems/linux/chapters/security.md)**
    1. Basic Linux Security Concepts
    2. AppArmor

## Essential Prerequisites

* Basics of computer science
    * Understanding of operating systems.
    * Basic knowledge of how a computer works (memory, CPU, storage etc.)

## Recommended Prerequisites

* Understanding the functionality and use of a computer's operating system.
* Basic knowledge of command line functionality.
* Knowledge on installing software on a computer system.