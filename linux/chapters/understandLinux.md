# 1. Understanding Linux

- This Chapter is not very practical but may as well be the most important
  chapter in this whole roadmap. It focuses on the history of Linux, the
  different distributions, and the jargon used in the Linux community, all of
  which are needed to understand the Linux ecosystem and get proper help online
  if you get stuck.
- There's no right path to linux, but this is definitely one of the best places
  to start learning about linux.
- Resources consulted writing those nodes are linked below.
- [Article - What is Linux?](https://webtribunal.net/blog/what-is-linux/) - Web
  Tribunal
- [Article - The History of Linux](https://www.linux.com/what-is-linux/) - Linux.com


## 1.A What is Linux?

- Linux is an UNIX inspired operating system. It is free and open source and
  it's used in many devices, from supercomputers to smartphones.
- Just to make sure we are all on the same page. Here's a definition for the
  operating system: An operating system is software that manages
  all the hardware resources associated with your desktop or laptop. To
  put it simply, the operating system manages the communication between your
  software and your hardware. Without the operating system (often referred
  to as the "OS"), the software wouldn't function.

### 1.AA Bootloader Introduction

- The software that manages the boot process of your
  computer. For most users, this will simply be a splash screen that
  pops up and eventually goes away to boot into the operating system.
- At the time of writing, the most popular bootloaders are GRUB and
  systemd-boot. Other bootloaders exist, but they are not nearly as popular.
- [Documentation - Arch Boot Process](https://wiki.archlinux.org/title/Arch_boot_process)
- [Documentation - systemd-boot](https://wiki.archlinux.org/title/Systemd-boot)
- [Documentation - GRUB](https://wiki.archlinux.org/title/GRUB)

### 1.AB Kernel Introduction

- This is the one piece of the whole that is actually
  called "Linux." The kernel is the core of the system and manages the
  CPU, memory, and peripheral devices. The kernel is the "lowest" level
  of the OS.
- [Documentation - Linux Kernel Troubleshooting](https://wiki.archlinux.org/title/Linux_kernel#Troubleshooting)

### 1.AC Daemons Introduction
- These are background services (printing, sound, scheduling, etc) that either
  start up during boot, or after you log into the desktop.
- SystemD is the most popular init system at the time of writing. It is
  responsible for starting and managing daemons.
- [Documentation - Systemd](https://wiki.archlinux.org/title/Systemd)

### 1.AD Shell Introduction
- You've probably heard mention of the Linux command line.
  This is the shell - a command process that allows you to control the
  computer via commands typed into a text interface. This is what, at
  one time, scared people away from Linux the most (assuming they had to
  learn a seemingly archaic command line structure to make Linux work).
  This is no longer the case. With modern desktop Linux, there is no
  need to ever touch the command line. Unless you want to do some advanced
  administrative tasks, there is nothing you need to type or learn in order
  to just use Linux.
- The most common shells are Bash, Zsh, and Fish. Bash is the default shell
  for most Linux distributions.
- [Documentation - Bash](https://wiki.archlinux.org/title/Bash)
- [Documentation - Zsh](https://wiki.archlinux.org/title/Zsh)
- [Documentation - Fish](https://wiki.archlinux.org/title/Fish)

### 1.AE Graphical Server Introduction
- This is the sub-system that displays the graphics
  on your monitor. In the past the only option was the X server but that
  has now been replaced by Wayland on most systems. Wayland is regarded
  as a simpler, faster and more secure system.
- [Video - Wayland Is Superior To Xorg: But It Doesn't Matter](https://www.youtube.com/watch?v=UW3nYiK3nd0) - Brodie Robertson

### 1.AF Desktop Environment Introduction
- This is the piece that the users actually interact with. There are many
  desktop environments to choose from (KDE, GNOME, Cinnamon, Enlightenment,
  XFCE, etc). Each desktop environment includes built-in applications
  (such as file managers, configuration tools, web browsers, games, etc.)
- [Documentation - Desktop Environment](https://wiki.archlinux.org/title/Desktop_environment)

### 1.AG Applications Introduction
- Desktop environments do not offer the full array of apps. Just like Windows
  and Mac, Linux offers thousands upon thousands of high-quality software
  titles that can be easily found and installed. Most modern Linux
  distributions (more on this in a moment) include App Store-like tools
  that centralize and simplify application installation. For example,
  Ubuntu Linux has the Ubuntu Software Center (a rebranding of GNOME
  Software) which allows you to quickly search among the
  thousands of apps and install them from one centralized location.

## 1.B Short History of Linux
- Here's a bit into the history of Linux. It's not very important to know
  this, but it's still interesting to know. It's also a good way to
  understand distro politics.
- [Video - Why so many distros? The Weird History of Linux](https://www.youtube.com/watch?v=ShcR4Zfc6Dw) - FireShip
### 1.BA Linux Kernel
- The Linux kernel was created in 1991 by Linus Torvalds. It was initially
  a hobby project, but it has since become the most widely used operating
  system kernel in the world. The Linux kernel is used in a wide variety
  of devices, including desktop computers, servers, mobile phones, tablets,
  and embedded devices.

### 1.BB GNU Project
- The GNU Project was launched in 1983 by Richard Stallman with the goal
  of creating a free operating system. The GNU Project has produced many
  of the components of the Linux operating system, including the GNU C
  Compiler (GCC) and the GNU C Library (glibc).
- The GNU Project was planned to be used with the Hurd kernel, but the
  Hurd kernel was not ready in time for the release of the GNU Project. 
  (Still isn't to this day) As a result, the Linux kernel was used instead.
- [Article - GNU Project](https://www.gnu.org/gnu/thegnuproject.en.html)

### 1.BC Linux Distributions
- First Linux distribution was MCC Interim Linux in 1992. It was followed by
  SLS Linux in 1992, Slackware Linux in 1993, and Debian Linux in 1993.
- [Image - GNU/Linux Distribution Timeline](https://upload.wikimedia.org/wikipedia/commons/1/1b/Linux_Distribution_Timeline.svg)

### 1.BD Linux Desktop Environments
- The first Linux desktop environment was CDE (Common Desktop Environment)
  in 1993. It was followed by KDE in 1996, GNOME in 1999, and Xfce in 1996.
- [Blog - GNU/Linux Desktop Environment Timeline](https://eylenburg.github.io/de_default.htm)

## 1.C Linux Distributions
- A Linux distribution is a collection of software based on the Linux kernel.
  It includes the Linux kernel, system utilities, an installation program,
  and usually a package manager. There are hundreds of Linux distributions,
  each with its own unique features and target audience.
- Linux's distributions might have completely different ideologies, but they
  all share the same kernel and most of the same software. The main
  differences between distributions are the package manager, the default
  desktop environment, and the default configurations.

### 1.CA Debian-based Distributions (e.g., Ubuntu, Debian)
- Debian is a Linux distribution that is known for its stability and
  security. It is one of the oldest Linux distributions and is the basis
  for many other popular distributions, including Ubuntu, Linux Mint, and
  elementary OS.
- Debian core ideology is to be 100% free software. This means that Debian
  does not include any proprietary software in its repositories, by default. 
  Debian also has a strict policy on software licensing. Debian only includes
  software licensed under a free software license.
- [Documentation - Debian](https://wiki.archlinux.org/title/Arch_compared_to_other_distributions#Debian)

### 1.CB RPM-based Distributions (e.g., Fedora, CentOS)
- RPM is a package manager used by Red Hat-based distributions, such as
  Fedora, CentOS, and Red Hat Enterprise Linux. RPM is a command-line
  tool that allows you to install, upgrade, and remove software packages.
- Fedora is a Linux distribution known for its bleeding-edge software. 
  It is the upstream distribution for Red Hat Enterprise Linux
  and CentOS. Fedora is a community-driven distribution sponsored
  by Red Hat.
- [Documentation - Fedora](https://docs.fedoraproject.org/en-US/fedora/latest/)

### 1.CC Others (e.g., Arch Linux, Gentoo)
- Arch Linux is a Linux distribution known for its simplicity and
  customizability. It is a rolling release distribution, which means
  that it is constantly being updated with the latest software.
- Gentoo is a Linux distribution known for its customizability and
  performance. It is a source-based distribution, which means that
  it is built from source code rather than pre-compiled binaries.
- [Documentation - Arch Linux](https://wiki.archlinux.org/title/Arch_Linux)
- [Documentation - Gentoo](https://www.gentoo.org/support/documentation/)

## 1.D Linux Jargon

- Linux (and Unix) have developed their own jargon over the years. This node
  contains are some of the most common terms you will come across.
- Jargon has been a major part keeping the linux community together and it's
  also something a lof of new users may struggle with. So it's important to
  learn the jargon.
- Oh, and... I use Arch btw.
- [Blog - The Jargon File](http://www.catb.org/jargon/html/index.html)
    - **Kernel**: The core of the operating system. It is responsible for
      managing the system's resources and providing an interface for user-level
      interaction.
    - **Distribution (Distro)**: A Linux distribution is a collection of
      software based on the Linux kernel. It includes the Linux kernel, system
      utilities, an installation program, and usually a package manager. There
      are hundreds of Linux distributions, each with its own unique features and
      target audience.
    - **Package Manager**: A package manager is a tool that automates the
      process of installing, upgrading, configuring, and removing software
      packages. It is a collection of software tools that work together to
      automate the process of installing, upgrading, configuring, and removing
      software packages from a computer.
    - **Desktop Environment (DE)**: A desktop environment is a collection of
      software designed to provide a consistent user experience across multiple
      applications and devices. It is a collection of software that provides a
      graphical user interface for a computer.
    - **Terminal**: A terminal is a program that allows you to interact with the
      computer using text commands. It is a program that allows you to interact
      with the computer using text commands.
    - **Shell**: A shell is a program that provides an interface for users to
      interact with the operating system. It is a program that provides an
      interface for users to interact with the operating system.
    - **Command**: A command is a program that performs a specific task. It is a
      program that performs a specific task.
    - **Command Line Interface (CLI)**: A command line interface is a text-based
      interface that allows users to interact with the operating system using
      text commands. It is a text-based interface that allows users to interact
      with the operating system using text commands.
    - **Graphical User Interface (GUI)**: A graphical user interface is a visual
      interface that allows users to interact with the operating system using
      graphical elements such as windows, icons, and menus. It is a visual
      interface that allows users to interact with the operating system using
      graphical elements such as windows, icons, and menus.
    - **File System**: A file system is a method of storing and organizing files
      on a computer. It is a method of storing and organizing files on a
      computer.
    - **File Permissions**: File permissions are a set of rules that determine
      who can access a file and what they can do with it. It is a set of rules
      that determine who can access a file and what they can do with it.