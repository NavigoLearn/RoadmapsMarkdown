# 11. Storage

- Storage in Linux involves managing hard drives, partitions, file systems, and
  files. Linux supports a variety of file systems such as ext4, XFS, and Btrfs,
  among others. Disk space is divided into partitions, each with its own file
  system. Tools like fdisk, parted, and df aid in managing these resources.
  Understanding storage management in Linux is essential for efficient use of
  disk resources and overall system operation.

## 11.A Partitioning

- Partitioning in Linux refers to the practice of splitting a single physical
  hard drive into multiple logical drives or partitions. This enables the
  separation of system files, user data, and swap space, providing improved data
  organization, performance, and security. Tools such as fdisk and parted are
  used for creating and managing partitions. Managing partitions effectively is
  a crucial part of Linux system administration.
- [Video - What are Drive Partitions?](https://www.youtube.com/watch?v=AeUM4kR67XQ)
- [Video - How Every Linux System Should Be Partitioned](https://www.youtube.com/watch?v=vUKRFyI3uPs)
- [Article - Create a Partition in Linux - A Step-by-Step Guide](https://www.digitalocean.com/community/tutorials/create-a-partition-in-linux)

## 11.B Mounting and Unmounting Filesystems

- Mounting and unmounting filesystems in Linux refers to the process of making a
  specific filesystem accessible to the operating system. When a filesystem is
  mounted, it attaches to an existing directory tree and becomes available for
  read and write operations. Conversely, unmounting a filesystem detaches it
  from the directory tree, making it inaccessible. Commands like mount and
  umount govern this process. Understanding this process is critical for
  managing access to storage devices and data in a Linux system.
- [Documentation - mount](https://manpages.org/mount/8)
- [Documentation - umount](https://manpages.org/umount/8)

## 11.C Disk Usage Analysis (df, du)
- In Linux, disk usage analysis is performed using utilities such as df and du.
The df command displays the amount of disk space used and available on
filesystems, providing a system-wide overview. Conversely, the du command
estimates file and directory space usage, offering a more granular inspection of
disk usage. Together, these tools facilitate effective disk management and help
prevent running out of storage space.
- [Documentation - df](https://manpages.org/df/1)
- [Documentation - du](https://manpages.org/du/1)