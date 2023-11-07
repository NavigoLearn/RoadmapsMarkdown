# 2. Basics of Linux Command Line

- Understanding the basics of the Linux command line is vital for a variety of
  reasons.
- It allows for greater efficiency as many tasks that would take multiple steps
  in a GUI can be accomplished quickly with a single command in the command
  line.
- This knowledge underpins the potential for script creation and automation,
  reducing repetitive tasks and enhancing productivity.
- If you're responsible for remote Linux servers, these systems are often
  managed exclusively via the command line, making this skill an indispensable
  part of your toolkit. This is further compounded by the fact that all Linux
  distributions include a command line interface, providing a level of
  cross-distribution compatibility.
- Many advanced and powerful tools such as grep, awk, sed, and git are utilized
  via the command line.
- The command line provides you with a wealth of learning opportunities around
  the inner workings of the Linux operating system, supporting your professional
  development and enabling you to exploit more advanced resources and guides.
- Basically, while user-friendly graphical interfaces are increasingly common in
  Linux distributions, command-line proficiency remains an invaluable skill at
  all user levels and is considered a fundamental area of knowledge in many tech
  roles.
-
- [Gamified Tutorial - Linux Survival](https://linuxsurvival.com)

## 2.A Navigating the File System

- The first step to using the command line is to understand how to navigate the
  file system.
- You can always use `man` to get more information about a command. For
  example, `man ls` will give you more information about the `ls` command.
- The important command here are `cd`, `ls`, and `pwd`. And here's a short
  explanation to what they do:
    - `cd` stands for change directory. It allows you to change your current
      working directory.
    - `ls` stands for list. It allows you to list the contents of a directory.
    - `pwd` stands for print working directory. It allows you to print the
      current working directory.
- [Documentation - cd](https://manpages.org/cd)
- [Documentation - ls](https://manpages.org/ls)
- [Documentation - pwd](https://manpages.org/pwd)

## 2.B File Operations

- The important commands here are `cp`, `mv`, and `rm`.
- `cp` stands for copy. It allows you to copy files and directories.
- `mv` stands for move. It allows you to move files and directories.
- `rm` stands for remove. It allows you to remove files and directories.
- You can use the `-r` flag with `cp` and `rm` to copy and remove directories
  recursively.
- [Documentation - cp](https://manpages.org/cp)
- [Documentation - mv](https://manpages.org/mv)
- [Documentation - rm](https://manpages.org/rm)

## 2.C Viewing File Contents

- The important commands here are `less`, `cat`, `tail`, and `head`.
- `less` allows you to view the contents of a file. It is a pager, which means
  it allows you to view files page by page.
  ex: `less file.txt`/`cat file.txt | less`
- `cat` allows you to view the contents of a file. It is a concatenation tool,
  which means it allows you to view multiple files at once.
- `tail` allows you to view the last few lines of a file. ex: `tail file.txt`
- `head` allows you to view the first few lines of a file. ex: `head file.txt`
- [Documentation - less](https://manpages.org/less)
- [Documentation - cat](https://manpages.org/cat)
- [Documentation - tail](https://manpages.org/tail)
- [Documentation - head](https://manpages.org/head)

## 2.D Utilities

- There's a lot of important command line utilities that you should know about.
  Here are some of them:
- `grep` allows you to search for a pattern in a file.
  ex: `grep "pattern" file.txt`
- `awk` allows you to manipulate text files. ex: `awk '{print $1}' file.txt` (
  prints the first column of a file)
- `sed` allows you to manipulate text files.
  ex: `sed 's/pattern/replacement/g' file.txt` (replaces all instances of a
  pattern with a replacement)
- `find` allows you to find files and directories.
  ex: `find . -name "pattern"` (finds all files and directories with a name
  matching the pattern)
- [Documentation - grep](https://manpages.org/grep)
- [Documentation - awk](https://manpages.org/awk)
- [Documentation - sed](https://manpages.org/sed)
- [Documentation - ](https://manpages.org/find)