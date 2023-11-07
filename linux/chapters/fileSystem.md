# 5. File System Architecture
- The file system architecture might be an important thing to consider when
  choosing Linux for your server.
- [Video - Linux File System in 4 Minutes](https://www.youtube.com/watch?v=995-SYn6960)

## 5.A File System Layout

- File Systems have been around for a long time. They are the reason why we can
  store data on our computers. They work to keep track of where data is stored
  on
  the hard drive. They may also have additional features like compression,
  encryption, logging, and more.
- The file system layout is the way the file system is organized. It is the way
  the files and directories are organized on the hard drive.
- The file system layout is different on different operating systems. For
  example, the file system layout on Windows (NTFS) is different from the file
  system layout on Linux (ext4).

## 5.B File Permissions and Ownership

- File permissions are a way to control who can access a file or directory. They
  are a way to control who can read, write, and execute a file or directory.
- File permissions are represented by three numbers: the first number represents
  the owner's permissions, the second number represents the group's permissions,
  and the third number represents everyone else's permissions.
- File permissions are represented by three letters: r (read), w (write), and x
  (execute). The permisisons can be seen in the output of `ls -l`.

## 5.C Understanding different File Systems (ext4, XFS, Btrfs etc.)

- There are many different file systems used on linux. The most common ones are
  ext4, XFS, and Btrfs.
- ext4 is the most common file system on linux. It is the default file system on
  most linux distributions.
- XFS is a file system that was designed for high-performance. It is the default
  file system on RHEL-based distributions.
- Here are some of the differences between ext4, XFS, and Btrfs:
- Btrfs is a file system that was designed for scalability. It is the default
  file system on SUSE-based distributions.
- EXT4 is better for small files and day-to-day use.
- XFS is better for larger files and long-term maintenance and stability.
- BTRFS has some fancy features and could help you manage your disk better in
  some automation-future-proof way. It's not faster or more stable than the
  other two.
- XFS supports partition size and file size up to 8 EiB, while EXT4 supports
  partition size up to 1 EiB and file size up to 16 TiB.
- XFS uses dynamically allocated inodes, while EXT4 does not.
- XFS can reach 64K for xattr (extended attributes) space, while EXT4 limits the
  length of xattr not to exceed one block (usually 4K).
- [Video - File Systems | Which One is the Best? ZFS, BTRFS, or EXT4](https://www.youtube.com/watch?v=HdEozE2gN9I)
- [Article - Linux 5.14 SSD Benchmarks With Btrfs vs. EXT4 vs. F2FS vs. XFS](https://www.phoronix.com/news/Linux-5.14-File-Systems)
