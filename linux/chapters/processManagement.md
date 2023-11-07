# 3. Process Management

- Using the command line to manage processes is a great skill to have. It allows
  you to manage processes on remote servers, and it allows you to automate
  processes.

## 3.A Process Listing and Monitoring

- The important commands here are `ps`, `top`, and `htop`. They all list
  processes, but they do it in different ways. Htop is the most user-friendly,
  but it is not installed by default on most systems.
- `ps` stands for process status. It allows you to list processes running in the
  current shell.
- `top` and `htop` allow you to list processes running on the system. It is an
  interactive process viewer.
- [Documentation - ps](https://manpages.org/ps)
- [Documentation - top](https://manpages.org/top)
- [Documentation - htop](https://manpages.org/htop)

## 3.B Process Control

- The important commands here are `kill`, `pkill` and `killall`. They both allow
  you to kill processes, but `pkill` is more user-friendly.
- `kill` allows you to kill a process by its PID.
- `pkill` allows you to kill a process by its name.
- `killall` allows you to kill all process with a given name.
- [Documentation - kill](https://manpages.org/kill)
- [Documentation - pkill](https://manpages.org/pkill)
- [Documentation - killall](https://manpages.org/killall)

### 3.BA Process Priorities and Niceness

- Processes have priorities. The higher the priority, the more resources the
  process will get. The lower the priority, the less resources the process will
  get.
- You can use the `nice` command to change the priority of a process.
- [Documentation - nice](https://manpages.org/nice)

### 3.BB Background and Foreground Processes

- Processes can be run in the background or in the foreground. When a process is
  run in the background, it is not attached to the current shell. When a process
  is run in the foreground, it is attached to the current shell.
- You can use the `&` symbol to run a process in the background. Or you can
  use `CTRL + Z` to suspend a process and then use the `bg` command to run it in
  the background.
- You can use the `fg` command to bring a process to the foreground.
- [Documentation - bg](https://manpages.org/bg)
- [Documentation - fg](https://manpages.org/fg)
- [Article - Job control](https://en.wikipedia.org/wiki/Job_control_(Unix))