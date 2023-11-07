# 10. Permissions and Privileges

- Permissions and Privileges on Linux define who can access the files and
  directories and what they can do with them. They are a foundational aspect of
  Linux' security model ensuring that only authorized users can read, write, or
  execute files. These permissions can be set for the owner of a file, a group,
  or others. Special privileges such as sudo allow certain users to execute
  commands with root or another user's privileges, providing fine-grained
  control
  over systems. Thus, properly managing permissions and privileges is critical
  for a secure and well-operated Linux system.

## 10.A Sudo and Root User

- Sudo, wheel group, and root user constitute critical aspects of Linux's
  security and authority model. Sudo is a command that allows users to execute
  commands with the security privileges of another user, typically the root
  user. The root user is the superuser and has the highest level of access to
  the system and files. The wheel group is a special user group in Linux, often
  used to control which users have sudo privileges. This effectively allows
  certain users to perform administrative tasks, tightly controlling system
  access and maintaining system integrity and security.
- [Video - How to use sudo su root](https://www.youtube.com/watch?v=NJpHKpdRZxc)
- [Article - sudo command in Linux](https://www.geeksforgeeks.org/sudo-command-in-linux-with-examples/)

## 10.B Changing File Permissions and Ownership
- In Linux, file permissions and ownership control access to files. The chmod
  command changes permissions (read, write, execute), and `chown` and `chgrp`
  commands change the user and group ownership respectively. Properly managing
  these is key to ensuring system security and efficient access control.
- [Video - Linux File Permissions in 5 Minutes](https://www.youtube.com/watch?v=LnKoncbQBsM)
- [Article - Linux File Permissions](https://www.guru99.com/file-permissions.html)


## 10.C Understanding setuid, setgid and Sticky Bit
- In Linux, `setuid`, `setgid`, and the `sticky bit` are special permission bits that extend or adjust the usual method of access control. setuid and setgid bits, when set on a file, alter the effective user or group ID respectively during the execution of that file, allowing users to run the program with the permissions of the file owner or group. This is useful for programs that need higher permissions than those granted to regular users. The sticky bit, when set on a directory, restricts file deletion within that directory. Only the owner of the file, the owner of the directory, or the root user can delete a file in a directory with the sticky bit set. These special permissions facilitate fine-grained control over file permissions and enhance security in a Linux system.
- [Video - https://www.youtube.com/watch?v=-BDmmlgF1kM](https://www.youtube.com/watch?v=-BDmmlgF1kM)
- [Article - Classic SysAdmin: Understanding Linux File Permissions](https://www.linux.com/training-tutorials/understanding-linux-file-permissions/)

## 10.D Understanding SELinux
- SELinux, short for Security-Enhanced Linux, is a set of security modules that extend the default Linux security measures. It uses Mandatory Access Controls (MAC) to limit the capabilities of system processes and users. This means a process or user only gets access to the resources it requires to function and no more, thus reducing potential system damage that can be caused by malicious or compromised processes. SELinux provides a flexible and robust security mechanism against unauthorized access, enforcing its rules even on the root user, adding an additional protective layer to the Linux operating system.
- SELinux is enabled by default on Fedora-based distributions, such as Fedora, CentOS, and RHEL. It can be disabled by editing the `/etc/selinux/config` file and setting `SELINUX=disabled`. It can also be temporarily disabled by running `setenforce 0`. To re-enable SELinux, run `setenforce 1`.
- [Video - What is SELinux?](https://www.youtube.com/watch?v=KkTDdHDAaYI)
- [Article - What is SELinux?](https://www.redhat.com/en/topics/linux/what-is-selinux)